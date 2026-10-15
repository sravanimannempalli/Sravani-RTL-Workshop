# 2 — Checking Optimization Results

## Objective
Practice reading synthesis output and explaining why the tool changed a design.

## Procedure
1. Keep a copy of the original RTL.
2. Run synthesis using the exercise's specified commands.
3. Save the synthesis log and generated netlist.
4. Identify changes in logic structure or statistics.
5. Check whether each change is consistent with the original design's function.

## Questions for analysis
- Were constants propagated?
- Were unused outputs or internal signals removed?
- Did the number or type of cells change?
- Does the optimized design still satisfy the testbench?

## Conclusion
Synthesis logs and netlists provide evidence of optimization. Record observed results rather than assuming a particular transformation occurred.
