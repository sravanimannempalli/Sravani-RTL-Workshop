# Lab 7 — Observing Synthesis Optimizations

## Objective
Explore how synthesis simplifies logic when constants, unused signals, or redundant operations are present.

## Common transformations
- Constant propagation: known values are carried through logic.
- Dead-code removal: logic that cannot affect an observable output may be removed.
- Boolean simplification: equivalent logic expressions may be reduced.
- Resource sharing or restructuring: implementation can change when the tool finds equivalent opportunities.

## Procedure
Compare a design before and after synthesis. Identify a transformation in the netlist or statistics and explain why it does not change the required output behavior.

## Important note
An optimized-away signal is not automatically an error. First check whether the signal affects any observable output or required side effect.

## Conclusion
Understanding optimization makes synthesized netlists easier to interpret and encourages RTL that expresses intent clearly.
