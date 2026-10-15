# Lab 5 — Hierarchical and Flattened Synthesis

## Objective
Compare how module hierarchy is treated during synthesis.

## Concepts
Hierarchical synthesis works with a design organized into modules. Flattened synthesis expands hierarchy so that optimizations can potentially cross module boundaries.

## Procedure
1. Prepare a design containing more than one module.
2. Run the specified synthesis flow while preserving hierarchy.
3. Run the equivalent flow with flattening enabled.
4. Inspect the resulting netlists and synthesis statistics.
5. Check that both implementations preserve the intended logic.

## Discussion
Flattening can expose additional optimization opportunities, but hierarchy may be valuable for readability, reuse, and design management. Results depend on the circuit and synthesis settings.

