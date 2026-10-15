# 2 — If Statements and Incomplete Assignments

An incomplete combinational `if` statement can infer a latch because the output must retain its previous value when no assignment occurs.

## Example concept
If an output is updated only when `enable` is true and no value is assigned when `enable` is false, the description implies storage rather than purely combinational behavior.

## How to review
1. List every possible condition.
2. Check whether each output receives an assignment on every path.
3. Run simulation with both asserted and deasserted conditions.
4. Review synthesis warnings and the resulting logic.
5. Decide whether storage was intended; if not, make the combinational assignments complete.

Do not remove a latch blindly if level-sensitive storage is part of the design specification.
