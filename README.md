# SAP-1 Computer – Logisim Implementation
My implementation of the **SAP-1 (Simple As Possible Computer)**, as proposed by Malvino & Brown, using the Logisim digital circuit simulator, with any modifications 

This project demonstrates the fundamental concepts of computer architecture through a fully functional 8-bit educational processor.

---

## 📚 About the SAP-1

The SAP-1 is a simplified computer model designed for teaching purposes. It illustrates how a basic CPU works, including:

- Instruction execution cycle (fetch-decode-execute)
- Data flow between registers
- Arithmetic and logic operations
- Memory addressing and control signals

---

## ⚙️ Features

- 8-bit architecture  
- Program Counter (PC)  
- Memory Address Register (MAR)  
- Random Access Memory (RAM)  
- Instruction Register (IR)  
- Accumulator (A Register)  
- B Register  
- Arithmetic Logic Unit (ALU)  
- Output Register  
- Control Unit (sequencer + control signals)  
- Shared bus system  

---

## 🧠 Instruction Set (extended)

| Instruction| Description              | op-code
|------------|--------------------------|--------
| LDA        | Load data into A register| 0xh
| ADD        | Add value to A           | 1xh
| SUB        | Subtract value from A    | 2xh
| OUT        | Output accumulator value | e0h
| HLT        | Halt execution           | f0h
| JMP        | Jumper to adress         | 3xh
| STA        | Copy A register to adress| cxh

*** note that 'x' is an adress position ***
---

## 🛠️ Tools Used

- Logisim / Logisim Evolution  
- Digital logic design principles  

---

## 🎓 Educational Purpose

This project is intended for:

- Computer Architecture courses  
- Digital Systems classes  
- Engineering and Computer Science students  
- Hands-on learning of CPU design  

It can be used to demonstrate how a simple processor is built from logic gates and registers.

---

## 🖼️ Screenshots

> the images of my circuits will be posted here (ALU, Control Unit, Full System)
