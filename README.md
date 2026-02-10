# Software-Based ASIC Design Using Verilog & Yosys
  (MIHIKA ZODAPE)

## Overview
This project demonstrates a complete ASIC-style design flow using software tools.

## Tools Used
- Verilog HDL
- Yosys
- Graphviz
- Ubuntu (WSL)

## Design Flow
Verilog → RTL Synthesis → Gate-Level Netlist → Circuit Diagram

## Output
![Gate-Level Design](counter_design.png)

## How to Run
yosys -p "read_verilog counter.v; synth; show -format png -prefix counter_design"
