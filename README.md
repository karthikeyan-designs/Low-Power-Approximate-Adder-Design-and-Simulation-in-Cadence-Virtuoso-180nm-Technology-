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

   ## 📷 Screenshots

### 🔸 TGA 1 Circuit Schematic  
![TGA 1 Schematic](screenshots/TGA1_Schematic.png)

### 🔸 Transient Simulation Waveform  
![Waveform](screenshots/TGA1_Simulation_Results.png)

### 🔸 TGA 1 Power Graph  
![TGA 1 Schematic](screenshots/TGA1_Power_Graph.png)

### 🔸 TGA 1 Average Power 
![Waveform](screenshots/TGA1_AveragePOWER.png)

