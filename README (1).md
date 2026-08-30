
# RTL Design workshop

This repository documents my learnings, simulations, waveforms, results of Digital Circuits.
In this repository, I have included all my learnings from the first 4 weeks of the program.



## Tools Used



Language- Verilog

Tool- Icarus Verilog

Tool- GTKWave

Tool- yosys

PDK- SKY130
## Learnings
This repository contains the complete RTL-to-Gate-Level Simulation (GLS) flow performed on two designs:

Good Mux

VSDBabySoC

The objective of this work is to understand and implement the digital design flow starting from RTL design and functional verification, followed by logic synthesis and Gate-Level Simulation (GLS).

The complete flow includes:

RTL Design → Functional Simulation → Synthesis → Gate-Level Simulation

## Good Mux
The Good Mux design was implemented and verified through the complete RTL-to-GLS flow.

Flow Performed:
RTL design

Functional simulation

Functional synthesis

Synthesized netlist simulation

Gate-Level Synthesis (GLS)

Gate-Level Simulation

Waveform verification using GTKWave


The simulation waveforms were analyzed to verify that the synthesized design behaves consistently with the original RTL implementation.
## VSDBabySoC
The same RTL-to-GLS methodology was applied to the VSDBabySoC design.

Flow Performed:
RTL/Pre-synthesis simulation

Functional synthesis

Synthesized netlist generation

Gate-Level Synthesis setup

Gate-Level Simulation

VCD waveform generation

Waveform analysis using GTKWave

The important signals were monitored during simulation to verify the functionality of the SoC after synthesis.
## Design Flow
RTL → Functional Simulation

The RTL design was first simulated using the testbench to verify the expected logical functionality.

Functional Synthesis

The verified RTL was synthesized to generate the corresponding gate-level netlist.

GLS Synthesis

The synthesized design was prepared for Gate-Level Simulation using the required standard-cell libraries and supporting modules.

GLS Simulation

The gate-level netlist was simulated with the testbench and the generated waveforms were inspected using GTKWave.
## Verification
The generated VCD waveforms were analyzed using GTKWave.

For VSDBabySoC, important internal and output signals were monitored to check whether the synthesized implementation maintained the expected behavior of the RTL design.

The comparison between pre-synthesis and post-synthesis simulation helped verify the correctness of the synthesis flow.
## Key Learnings
Through this implementation, I gained practical understanding of:

RTL design and verification

Functional simulation

Logic synthesis

Netlist generation

Gate-Level Simulation

Standard-cell based synthesis

VCD waveform generation

Debugging simulation and synthesis issues

Using Icarus Verilog and GTKWave

Understanding differences between RTL and synthesized designs
## Conclusion
I gained hands-on experience with the complete RTL-to-Gate-Level Simulation flow.

Both Good Mux and VSDBabySoC were taken through synthesis and simulation stages, and their waveforms were analyzed to validate the synthesized implementation.

This workflow forms an important foundation for understanding VLSI digital design, synthesis, verification, and ASIC implementation flows.