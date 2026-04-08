# CMOS Inverter & VTC Analysis using LTspice

> Fundamental VLSI project demonstrating CMOS inverter design and characterization using LTspice.

---

## Overview
This project focuses on the design and simulation of a **CMOS inverter** using LTspice. It analyzes the inverter's switching behavior and evaluates its **Voltage Transfer Characteristics (VTC)**.

The CMOS inverter, built using complementary **PMOS** and **NMOS** transistors, is a key component in digital electronics and VLSI design.

---

## Objectives
- Design a CMOS inverter circuit using LTspice  
- Perform **transient analysis** to observe switching behavior  
- Perform **DC sweep analysis** to obtain the VTC curve  
- Determine switching threshold voltage (VM)  
- Analyze noise margins and gain  

---

## Circuit Description
The CMOS inverter consists of:
- PMOS transistor connected to VDD (pull-up network)  
- NMOS transistor connected to GND (pull-down network)  
- Input applied to both gates  
- Output taken from the common drain  

---

## Simulation Details

###  Transient Analysis
- Input: Pulse waveform (0V to 5V)  
- Command:
```spice
.tran 10ms
