# Module 1 — RTL Design Foundations and Tool Setup

## Overview
This module introduces the basic workflow used to describe, simulate, and synthesize digital hardware. The exercises focus on becoming comfortable with the development tools and understanding how a Verilog design moves from source code to observable behavior.

## Topics Covered
- RTL design as a hardware description method
- Setting up Git, a text editor, Icarus Verilog, and GTKWave
- Writing a small Verilog module and a testbench
- Compiling and running a simulation
- Inspecting signal transitions in a waveform viewer
- Introduction to Yosys and logic synthesis

## Typical Workflow
1. Create or open the Verilog source file.
2. Write a testbench that applies input combinations.
3. Compile the source and testbench with Icarus Verilog.
4. Run the simulation and save a waveform file.
5. Inspect the waveform in GTKWave and compare it with the expected behavior.
6. Use Yosys to examine how the RTL can be represented as a logic network.

## Key Takeaways
Simulation helps check functional behavior, while synthesis translates RTL into a hardware-oriented representation. A waveform is most useful when the testbench exercises meaningful input cases and the expected results are known.

## Reflection
The main learning outcome is understanding the connection between Verilog code, testbench stimulus, simulation output, and the synthesized logic structure.


