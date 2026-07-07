# CODETECH_TASK2

## 4-Bit Ripple Carry Adder using Verilog HDL

### Project Overview

This project implements a 4-Bit Ripple Carry Adder using Verilog HDL. The design consists of four Full Adders connected in series, where the carry output from each Full Adder is propagated to the next stage. Ripple Carry Adders are fundamental arithmetic circuits widely used in digital systems and VLSI design. The design was simulated and verified using EDA Playground and EPWave.

---

## Objectives

- Design a 4-Bit Ripple Carry Adder using Verilog HDL.
- Implement the adder using Full Adder modules.
- Verify the functionality through simulation and waveform analysis.
- Understand binary addition and carry propagation in digital circuits.

---

## Tools Used

- Verilog HDL
- EDA Playground
- EPWave
- GitHub

---

## Project Files

- `design.v.txt` – Verilog module implementing the 4-Bit Ripple Carry Adder.
- `testbench.v.txt` – Testbench for verifying different input combinations.
- `waveform.png` – Simulation waveform of the Ripple Carry Adder.

---

## Test Cases

| A | B | Cin | Sum | Cout |
|---|---|-----|------|------|
| 0000 | 0000 | 0 | 0000 | 0 |
| 0011 | 0101 | 0 | 1000 | 0 |
| 1111 | 0001 | 0 | 0000 | 1 |
| 1010 | 0110 | 1 | 0001 | 1 |
| 1111 | 1111 | 0 | 1110 | 1 |

---

## Simulation Results

The simulation successfully verified the operation of the 4-Bit Ripple Carry Adder for multiple input combinations. The output sum and carry-out matched the expected binary addition results. The waveform generated in EPWave clearly demonstrated the propagation of the carry signal through each Full Adder stage.

---

## Waveform

### Ripple Carry Adder Waveform

![Ripple Carry Adder Waveform](waveform.png)

---

## Conclusion

This project demonstrates the design and simulation of a 4-Bit Ripple Carry Adder using Verilog HDL. The design was successfully verified through simulation using EDA Playground and waveform analysis using EPWave. The project provides a practical understanding of binary addition, Full Adder implementation, and carry propagation, which are essential concepts in digital electronics and VLSI design.# Ripple-carry
