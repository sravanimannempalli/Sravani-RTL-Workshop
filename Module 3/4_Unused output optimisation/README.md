# 4 — Unused Logic and Output Optimization

## Objective
Explore how synthesis treats signals and logic that do not contribute to required outputs.

## Concepts
Synthesis typically preserves logic needed to implement observable behavior. Logic that cannot affect a top-level output or other modeled requirement may be removed.

## Procedure
1. Inspect the module outputs and internal signals.
2. Identify signals that are not consumed by downstream logic.
3. Run the assigned synthesis flow.
4. Review the netlist and reports for removed or simplified logic.
5. Check the remaining logic against the specification.

## Conclusion
Clear module interfaces and purposeful signal usage make synthesis results easier to understand. Confirm every optimization against the intended functionality.
