# 3 — Sequential Optimization Techniques

## Objective
Understand why optimization of sequential logic requires attention to state and clock behavior.

## Discussion
Registers store state between clock events. A synthesis tool can sometimes simplify a register or its surrounding logic when constants or equivalent conditions make part of the state unnecessary.

## Analysis steps
- Identify the clock and reset conditions.
- Determine which state bits can influence outputs.
- Inspect the RTL for constant assignments or redundant updates.
- Compare the inferred registers before and after optimization.
- Verify behavior using simulation or an appropriate equivalence check.

## Caution
Do not infer that a register is redundant just because it appears unused in one test. Consider all legal input sequences and the design specification.
