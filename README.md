# 2-D TCAD Simulation of a Silicon PN Diode (Silvaco Victory Device)

This project demonstrates a full 2-D TCAD simulation of a silicon PN diode using **Silvaco Victory Device** on **nanoHUB**.  
The goal is to analyze diode operation through band diagrams, carrier concentrations, electric field profiles, depletion width extraction, and I–V characteristics.  
Analytical calculations are compared with TCAD results to validate semiconductor physics.

---

## 🧭 Project Overview

This simulation models an **abrupt PN junction diode** with:

- P-type doping: \(1 \times 10^{17} 
- N-type doping: \(1 \times 10^{16}
- Silicon material model  
- 2-D rectangular geometry  
- Silvaco physical models (conmob, fldmob, SRH, Auger, BGN)

The simulation sweeps voltage from reverse bias (–1 V) into forward bias (up to +1 V) and extracts:

- 2-D doping profile  
- Conduction & valence band diagrams  
- Electron & hole concentrations  
- Electric field profile  
- I–V characteristics  
- Depletion width under reverse bias  
- Effective barrier height  
- Comparison with analytical semiconductor equations  

This project is intended to demonstrate **device physics understanding**, **TCAD modeling skills**, and **engineering documentation quality**.

---

## 📁 Repository Structure

