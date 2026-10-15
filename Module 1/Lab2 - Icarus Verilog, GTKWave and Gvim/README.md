# Lab 2 — Simulation and Waveform Inspection

## Objective
Practice the edit–compile–simulate–inspect cycle using a small combinational circuit.

## Procedure
1. Review the module ports and logic.
2. Prepare a testbench with input combinations that cover the function.
3. Compile the design and testbench with Icarus Verilog.
4. Run the generated simulation executable.
5. Open the waveform file in GTKWave.
6. Compare the output against the expected truth table.

## What to check
- Every relevant input combination is exercised.
- The waveform contains the signals needed for debugging.
- Output transitions match the design's logic.
- Testbench timing gives the simulator enough time to apply and observe each case.

## Conclusion
Waveform inspection provides a visual way to confirm signal behavior and locate mistakes in stimulus or RTL.
