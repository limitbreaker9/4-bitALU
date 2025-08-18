# Custom Sequence Counter (Logisim)

## 🔹 Project Overview
This project implements a **custom counter** in Logisim that does not follow the normal binary up/down counting.  
Instead, it follows a **user-defined sequence of states** using Flip-Flops and combinational logic.

## 🔹 Sequence Implemented
The counter progresses through the following 16 states:
15 → 14 → 11 → 3 → 5 → 12 → 13 → 6 → 10 → 1 → 4 → 9 → 7 → 8 → 2 → 0 → (repeat)

- Total **16 unique states** (covers all possible 4-bit combinations)  
- Implements **nonlinear state transitions**  
- Returns to `15` after reaching `0`

## 🔹 Design Details
- Built using **D Flip-Flops** for state storage  
- **Next state logic** derived using K-Maps and Boolean minimization  
- Demonstrates the concept of **Finite State Machines (FSMs)**  
- Clock-driven, fully synchronous design  

## 🔹 Applications
- Learning tool for understanding **state machine design**  
- Demonstrates **sequence generation** beyond natural binary counting  
- Can be extended for **pseudo-random number generation** or specific control sequences  

## 🔹 Files in this Project
- `Counter.circ` → Logisim project file  
- `README.md` → Project description (this file)  
- `sequence_diagram.png` → State diagram of custom sequence (if added)  

---
