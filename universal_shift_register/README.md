# Universal Shift Register (Logisim)

## 🔹 Project Overview
This project implements a **Universal Shift Register** in Logisim.  
A universal shift register is a versatile digital circuit that can perform **multiple operations** on stored data depending on the control inputs.

## 🔹 Features
The register supports the following operations:
1. **Hold** → Maintain the current data  
2. **Shift Left** → Move all bits one position left, input enters from the right  
3. **Shift Right** → Move all bits one position right, input enters from the left  
4. **Parallel Load** → Load external data directly into the register  

## 🔹 Design Details
- Built using **D Flip-Flops** as storage elements  
- **Multiplexers** control data input based on the mode select lines  
- Control signals determine the operation:  
  - `00` → Hold  
  - `01` → Shift Right  
  - `10` → Shift Left  
  - `11` → Parallel Load  
- Fully synchronous, clock-driven design  

## 🔹 Applications
- Temporary data storage  
- Serial-to-parallel and parallel-to-serial conversion  
- Data manipulation in CPUs and digital systems  
- Basis for designing more complex registers and memory units  

## 🔹 Files in this Project
- `Universal_Register.circ` → Logisim project file  
- `README.md` → Project description (this file)  
- `universal_register.png` → Circuit diagram (if added)  

---
