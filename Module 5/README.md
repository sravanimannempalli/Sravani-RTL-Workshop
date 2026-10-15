# Module 5 — Conditional Logic, Case Statements, and Loops

## Overview
This module studies common Verilog constructs used to describe decision-making and repeated structures, with attention to the hardware inferred by synthesis.

## Topics
- `if` / `else` decision logic
- `case` statements and selection logic
- Complete versus incomplete assignments
- Latch inference
- Loop constructs and elaboration-time `generate` statements

## Conditional Assignments
For combinational logic, each output should be assigned for every possible control path. If an output is left unassigned on some path, the design may require storage of its previous value, leading to latch inference.

## Case Statements
A `case` statement should account for all intended input values. A `default` branch can make behavior explicit for unlisted values, but its correct use depends on the design specification.

## Loops
Procedural loops and generate constructs serve different purposes. Generate constructs create repeated hardware structures during elaboration; procedural loops execute within a procedural block according to the language semantics.

## Key Takeaway
Always inspect synthesis warnings and inferred hardware when using conditional and loop constructs.
