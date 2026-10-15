# 3 — Case Statement Completeness

## Objective
Examine how complete and incomplete `case` statements affect simulation and hardware inference.

## Procedure
- Identify the selector and its possible values.
- Review each case item and the default behavior.
- Ensure the intended outputs are assigned consistently.
- Simulate ordinary and unlisted selector values.
- Inspect synthesis output for latch inference or unexpected logic.

## Important distinction
A default branch defines behavior for values not explicitly listed. The correct default value should follow the specification, not be chosen only to silence a warning.

## Conclusion
Complete and intentional case descriptions make both functional verification and synthesis interpretation more reliable.
