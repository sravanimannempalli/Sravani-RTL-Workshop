# Module 4 — Gate-Level Simulation and RTL/Synthesis Mismatches

## Overview
This module introduces gate-level simulation (GLS) and coding patterns that may cause simulation behavior to differ from synthesized hardware.

## Topics Covered
- RTL simulation compared with gate-level simulation
- Blocking and non-blocking assignments
- Sensitivity-list completeness in procedural combinational logic
- Incomplete mux descriptions
- Synthesized netlist verification

## RTL vs. GLS
RTL simulation evaluates the behavioral description. Gate-level simulation evaluates the synthesized netlist and may include library models and timing information, depending on the setup. Both require suitable testbenches and models.

## Common Sources of Mismatch
- Incomplete sensitivity lists in older Verilog procedural blocks
- Blocking assignments used in sequential logic in ways that create ordering issues
- Incomplete assignments that infer latches
- Incomplete `if` or `case` branches
- Missing or incompatible simulation models

## Debugging Approach
Use the same test vectors for RTL and gate-level simulations, compare outputs at meaningful times, and inspect warnings and unknown values. Confirm that the correct netlist and cell models are compiled.

## Key Takeaway
Careful RTL coding and consistent verification reduce the chance of simulation–synthesis mismatches.
