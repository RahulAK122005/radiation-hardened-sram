# Radiation Hardened SRAM

> Radiation-hardened SRAM design for mitigating Single Event Upsets (SEUs).
---
## Project Overview
Traditional **6T SRAM** cells are highly susceptible to radiation-induced **Single Event Upsets (SEUs)**, especially in **space**, **satellite**, **automotive**, and **safety-critical** applications.

This project investigates radiation hardening techniques by comparing a conventional 6T SRAM cell with a DICE SRAM architecture. The design was implemented and simulated in Cadence Virtuoso, and transient current injection was used to emulate particle strikes and analyze SEU robustness.


## Project Objectives
This project aims to improve the reliability of SRAM cells against radiation-induced Single Event Upsets (SEUs). The key objectives are:
- Design a conventional **6T SRAM** cell.
- Analyze **Read, Write, and Hold** operations.
- Evaluate the **Static Noise Margin (SNM)** using the butterfly curve.
- Simulate **radiation-induced Single Event Upsets (SEUs)** using transient current injection.
- Calculate the **Critical Charge (Qcrit)** required to cause a bit flip.
- Design and analyze a **DICE (Dual Interlocked Storage Cell) SRAM** architecture.
- Compare the reliability and SEU tolerance of **6T SRAM** and **DICE SRAM** designs.

  
 ## Applications
This project is applicable in systems where memory reliability under radiation exposure is critical.
- Space Electronics
- Satellites
- Aerospace Systems
- Nuclear Electronics
- Automotive Safety Systems
- Military and Defense Electronics

