# VLSI Project 03 — D Flip-Flop + Counter Verification

## Overview

This project demonstrates the design and verification of a D Flip-Flop and a 4-bit Counter using Verilog HDL in Vivado.

The objective is to understand how digital circuits are designed, simulated, and verified using a testbench-driven approach. The project includes RTL design, simulation, waveform analysis, and automated pass/fail verification checks.

---

## Project Objectives

* Design a D Flip-Flop using Verilog HDL
* Design a 4-bit synchronous counter
* Integrate multiple RTL modules
* Develop a verification testbench
* Perform simulation in Vivado
* Analyze waveform results
* Generate pass/fail verification reports

---

## Tools Used

| Tool          | Purpose                       |
| ------------- | ----------------------------- |
| Vivado 2020.1 | RTL Design & Simulation       |
| Verilog HDL   | Hardware Description Language |
| XSIM          | Functional Simulation         |

---

## Project Structure

```text
VLSI-Project-03-DFF-Counter-Verification
│
├── dff.v
├── counter.v
├── top.v
├── top_tb.v
├── screenshots
│   ├── project_structure.png
│   ├── rtl_design.png
│   ├── testbench.png
│   ├── waveform.png
│   └── pass_report.png
│
└── README.md
```

## Design Description

### D Flip-Flop

The D Flip-Flop captures the input data (D) on every positive edge of the clock and stores it at the output (Q).

### 4-Bit Counter

The counter increments its value on every positive clock edge and resets to zero when reset is asserted.

---

## Verification Strategy

The verification testbench performs:

* D Flip-Flop functionality check
* Counter increment verification
* Counter reset verification
* Automated pass/fail reporting

---

## Expected Simulation Output

```text
PASS: DFF captured input
PASS: Counter incremented correctly
PASS: Counter reset correctly

Simulation Completed
```

---

## Waveform Verification

The waveform confirms:

* Proper clock generation
* Successful D Flip-Flop operation
* Correct counter increment sequence
* Successful reset functionality

Example:

```text
Count : 0 → 1 → 2 → 0
Q     : 0 → 1
```

---

## Key Concepts Learned

* Verilog HDL Fundamentals
* Sequential Logic Design
* D Flip-Flop Implementation
* Counter Design
* Testbench Development
* RTL Verification
* Waveform Analysis
* Simulation Debugging

---

## Future Improvements

* Add SystemVerilog Assertions (SVA)
* Functional Coverage
* Randomized Verification
* Advanced Verification Environment
* FPGA Hardware Implementation

---

## Author

Narasimha Lakkimsetty

B.Tech Electronics & Communication Engineering

VLSI | FPGA | Digital Design | Verification
