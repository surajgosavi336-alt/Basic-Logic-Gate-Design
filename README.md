# Basic Logic Gate Design using Verilog HDL

## 📌 Project Overview

This project implements the basic digital logic gates using Verilog HDL and verifies their functionality through simulation on EDA Playground.

The implemented logic gates are:

- AND Gate
- OR Gate
- NOT Gate
- XOR Gate
- NAND Gate
- NOR Gate

---

## 🎯 Objective

The objective of this project is to understand the fundamentals of digital logic design by implementing basic logic gates using Verilog HDL and verifying their outputs through simulation.

---

## 🛠️ Software Used

- Verilog HDL
- EDA Playground
- Icarus Verilog Simulator
- EPWave (Waveform Viewer)

---

## 📂 Project Structure

```
Basic-Logic-Gate-Design/
│── design.v
│── testbench.v
│── waveform.png
│── output.png
│── README.md
```

---

## 📖 Logic Gates Implemented

| Logic Gate | Operation |
|------------|-----------|
| AND | A & B |
| OR | A \| B |
| NOT | ~A |
| XOR | A ^ B |
| NAND | ~(A & B) |
| NOR | ~(A \| B) |

---

## 🧪 Test Cases

| A | B | AND | OR | NOT(A) | XOR | NAND | NOR |
|---|---|-----|----|--------|-----|------|-----|
| 0 | 0 | 0 | 0 | 1 | 0 | 1 | 1 |
| 0 | 1 | 0 | 1 | 1 | 1 | 1 | 0 |
| 1 | 0 | 0 | 1 | 0 | 1 | 1 | 0 |
| 1 | 1 | 1 | 1 | 0 | 0 | 0 | 0 |

---

## ▶️ Simulation

The design was simulated using **Icarus Verilog** on **EDA Playground**.

The testbench verifies all possible input combinations and generates a waveform for verification.

---

## 📊 Output

(Add your simulation output screenshot here)

Example:

```
A B | AND OR NOT XOR NAND NOR

0 0 | 0   0   1   0    1    1
0 1 | 0   1   1   1    1    0
1 0 | 0   1   0   1    1    0
1 1 | 1   1   0   0    0    0
```

---

## 📈 Waveform

(Add your EPWave screenshot here)

Example file:

```
waveform.png
```

---
