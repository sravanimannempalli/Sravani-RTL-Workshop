# Lab 6 — Flip-Flop Simulation and Synthesis

## Objective
Study how synchronous and asynchronous reset styles behave in simulation and how they are represented after synthesis.

## Procedure
1. Write a small register module using the reset style assigned in the exercise.
2. Create a testbench that checks normal clocked operation and reset assertion/deassertion.
3. Simulate the RTL and inspect the waveform.
4. Synthesize the design and inspect the inferred sequential cells.
5. Compare the observed behavior with the intended reset semantics.

## Checks
- Does the register update on the intended clock edge?
- Is reset active-high or active-low?
- Does reset take effect synchronously or asynchronously?
- Does the synthesized cell match the intended behavior?

## Conclusion
Simulation and synthesis inspection together help confirm that sequential RTL describes the intended storage element.
