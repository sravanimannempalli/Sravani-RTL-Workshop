# 1 — If and Case Constructs

## Objective
Describe selection logic using conditional statements and understand how branch coverage affects inferred hardware.

### If/else
An `if` statement selects behavior based on a condition. In combinational logic, assign every output on every path to avoid unintentionally retaining a previous value.

### Case
A `case` statement expresses selection among multiple alternatives. Include all required alternatives and consider a `default` branch for unlisted values.

### Review checklist
- Are all outputs assigned in every branch?
- Are priority and selection behavior intentional?
- Are all relevant input values handled?
- Do simulation results match the expected truth table?

Synthesis reports can help identify latches or other hardware inferred from incomplete descriptions.
