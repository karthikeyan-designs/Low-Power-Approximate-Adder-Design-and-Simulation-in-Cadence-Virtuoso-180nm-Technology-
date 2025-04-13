# Low-Power-Approximate-Adder-Design-and-Simulation-in-Cadence-Virtuoso-180nm-Technology-

Designed and simulated a low-power approximate adder using Cadence Virtuoso at 180nm CMOS.

## 📌 Project Overview

This repository contains the design and simulation of a low-power approximate full adder using **Cadence Virtuoso** with **180nm CMOS technology**. The project is based on the journal paper:

### 📝 LAHAF: Low-power, area-efficient, and high-performance approximate full adder based on static CMOS

The work focuses on reducing power consumption while maintaining acceptable performance, making it suitable for error-resilient applications such as **image processing**, **machine learning**, and **data mining**. Due to the human visual system’s tolerance to small inaccuracies, approximate computing is highly effective in applications involving image and video processing.

## 🔧 In this project:

-  The **TGA 1** circuit (as proposed in the journal) was implemented at the schematic level in **Cadence Virtuoso**.
-  **Functional simulation** was performed to verify the behavior of the full adder.
-  **Average power consumption** was estimated using **pre-layout transient analysis**.
-  This design demonstrates how approximate adders can achieve **low power dissipation**, **area efficiency**, and **high performance**, making them ideal for power-constrained systems.

---

## 📚 Reference

- **LAHAF: Low-power, area-efficient, and high-performance approximate full adder based on static CMOS**  
  *A. Khoshavi, S. Asgarinejad, S. K. Mohammadi, M. Fazeli*  
  [📎 ScienceDirect Link](https://www.sciencedirect.com/science/article/pii/S2210537921000226)
  ## Circuit Diagram

   ![TGA 1 Schematic](screenshots/TGA1_Circuit.png)
  ## 🧩 TGA 1 Circuit Description

The **TGA 1** approximate full adder is built using **16 transistors**, combining **Static CMOS logic** and **Transmission gate logic**. A key feature of this design is that the **carry-out (Cout)** is directly taken from the input **Bin**, meaning:

> **Cout = Bin**

This simplification significantly reduces the transistor count and power consumption, which are essential advantages for **approximate computing** applications such as image processing and machine learning, where perfect accuracy is not always necessary.

---

## 🧮 TGA 1 Equations

![TGA 1 Equations](screenshots/TGA1_Eq.png)

---

## 🔍 Comparison Between the Exact Full Adder and TGA1 Outputs

The table below compares the **sum** and **carry-out** outputs of the **exact full adder** and the **TGA1** approximate full adder. Mismatches are marked with a **✗**, while correct matches are indicated with a **✓**.

![Truth Table Comparison](screenshots/truth_table.png)

The **TGA1** circuit has an **Error Distance (ED)** of **2**, which measures the total deviation of its output from the exact full adder. This small error makes it suitable for applications where **energy efficiency** is more important than **perfect accuracy**.


   ## 📷 Schematic & Simulation Results

### 🔸 TGA 1 Circuit Schematic  
![TGA 1 Schematic](screenshots/TGA1_Schematic.png)


### 🔸 Transient Simulation Waveform  
![Waveform](screenshots/TGA1_Simulation_Results.png)

### 🔸 TGA 1 Power Graph  
![TGA 1 Schematic](screenshots/TGA1_Power_Graph.png)

### 🔸 TGA 1 Average Power 
![Waveform](screenshots/TGA1_AveragePOWER.png)

