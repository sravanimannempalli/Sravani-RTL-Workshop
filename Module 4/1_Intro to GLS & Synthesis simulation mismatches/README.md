# 1 — Introduction to Gate-Level Simulation

Gate-level simulation checks the behavior of a synthesized netlist rather than the original RTL description.

## Why use it?
It can help validate that the synthesized representation behaves as expected when the required cell models and testbench are available.

## RTL and gate-level differences
- RTL focuses on the intended behavior at an abstract level.
- A gate-level netlist contains mapped cells and interconnections.
- Timing-aware GLS can include cell and interconnect delays when supported by the setup.

## Potential mismatch sources
Incorrect RTL constructs, incomplete assignments, missing models, or inconsistent compile inputs can cause results to differ.

## Verification checklist
- Confirm the intended netlist is compiled.
- Include the required standard-cell simulation models.
- Apply the same input sequence used for RTL checks.
- Inspect warnings, unknown values, and output timing.
