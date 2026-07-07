# CODETECH_TASK1

## Basic Logic Gate Design using Verilog HDL

### Project Overview

This project implements the fundamental digital logic gates using Verilog HDL. The implemented logic gates include AND, OR, NOT, XOR, NAND, and NOR gates. These gates form the building blocks of digital circuits and are widely used in VLSI design. The design was simulated and verified using EDA Playground and EPWave.

---

## Objectives

- Design basic logic gates using Verilog HDL.
- Implement AND, OR, NOT, XOR, NAND, and NOR gates.
- Verify the functionality through simulation and waveform analysis.
- Understand the fundamentals of combinational logic design used in VLSI systems.

---

## Tools Used

- Verilog HDL
- EDA Playground
- EPWave
- GitHub

---

## Project Files

- `design.v.text` – Verilog module implementing the basic logic gates.
- `testbench.v.txt` – Testbench for simulating all input combinations.
- `waveform output.png` – Simulation waveform of the logic gates.


---

## Logic Gate Truth Table

| A | B | AND | OR | NOT(A) | XOR | NAND | NOR |
|---|---|-----|----|--------|-----|------|-----|
| 0 | 0 | 0 | 0 | 1 | 0 | 1 | 1 |
| 0 | 1 | 0 | 1 | 1 | 1 | 1 | 0 |
| 1 | 0 | 0 | 1 | 0 | 1 | 1 | 0 |
| 1 | 1 | 1 | 1 | 0 | 0 | 0 | 0 |

---

## Simulation Results

The simulation successfully verified the functionality of all six logic gates. Each input combination produced the expected output according to the corresponding truth table. The waveform generated in EPWave confirmed the correct logical behavior of the implemented gates throughout the simulation.

---

## Waveforms

### Logic Gate Waveform

![Logic Gate Waveform](waveform%20output.png)



## Conclusion

This project demonstrates the design and simulation of the fundamental digital logic gates using Verilog HDL. The AND, OR, NOT, XOR, NAND, and NOR gates were successfully implemented and verified through simulation using EDA Playground and waveform analysis using EPWave. The project provides a strong foundation in combinational logic design and Verilog programming, which are essential concepts in VLSI design and digital system development.
