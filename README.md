# 64-bit-Vedic-Multiplier-CSA-KSA
Design and Implementation of a 64-bit Vedic Multiplier using Carry Save Adder, Kogge-Stone Adder, Pipelining and Clock Enable Optimization.
# 64-bit Vedic Multiplier Using CSA and Kogge-Stone Adder

## Project Overview
Design and implementation of a 64-bit hierarchical Vedic multiplier using Carry Save Adder (CSA) compression and a 128-bit Kogge-Stone Adder (KSA).

The architecture incorporates pipelining, clock-enable-based optimization and operand isolation to improve implementation efficiency.

## Tools and Technologies
- Verilog HDL
- Xilinx Vivado 2023.1
- Kintex-7 FPGA (XC7K70T-FBV676-1)

## Architecture
- 64×64 hierarchical Vedic multiplication
- 3:2 Carry Save Adder compression
- 128-bit Kogge-Stone parallel-prefix adder
- Four-stage pipelined architecture
- Clock-enable-based power optimization
- Operand isolation

## Implementation Results

### Power Analysis
- Estimated Total On-Chip Power: 0.361 W
- Estimated Dynamic Power: 0.279 W
- Estimated Static Power: 0.082 W
- Estimated Junction Temperature: 25.7°C

### Timing Analysis
- Worst Negative Slack (WNS): +3.703 ns
- Total Negative Slack (TNS): 0 ns
- Worst Hold Slack (WHS): +0.062 ns
- Setup Violations: 0
- Hold Violations: 0

## Verification
Functional verification performed using a self-checking Verilog testbench with directed and randomized test cases.

## Target Device
XC7K70T-FBV676-1 (Kintex-7)

## Disclaimer
Results are based on Vivado 2023.1 post-implementation analysis. No physical FPGA board measurements were performed. Power estimation confidence was reported as LOW.

## Author
VLSI / Digital Design Project
