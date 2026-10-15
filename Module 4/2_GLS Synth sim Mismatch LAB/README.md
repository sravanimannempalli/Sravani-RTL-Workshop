# 2 — Investigating a Synthesis/Simulation Mismatch

## Objective
Use a small example to understand how RTL coding style can affect simulation and synthesized behavior.

## Procedure
1. Run the RTL testbench and note the output for each test case.
2. Synthesize the design using the assigned flow.
3. Run gate-level simulation with the correct netlist and cell models.
4. Compare the outputs using identical input stimulus.
5. If a difference appears, inspect assignments, sensitivity lists, and branch completeness.

## Debugging notes
An unknown output may come from uninitialized state, missing models, or an invalid simulation setup; it is not always evidence of a synthesis bug.

## Conclusion
A controlled comparison between RTL and GLS is more useful than comparing waveforms generated with different input sequences.
