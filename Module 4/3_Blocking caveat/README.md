# 3 — Blocking Assignment Caveats

Blocking assignments (`=`) update a variable immediately within the procedural execution order. Non-blocking assignments (`<=`) schedule updates for the end of the current simulation time step and are commonly used for clocked state.

## Why coding style matters
Procedural ordering can affect simulation results, especially when multiple assignments or processes interact. A coding pattern may therefore be difficult to reason about or may not express the intended hardware clearly.

## Good practice
- Use non-blocking assignments for clocked sequential logic in typical RTL style.
- Use blocking assignments for many combinational procedural descriptions.
- Avoid multiple processes driving the same variable.
- Check synthesis warnings and compare simulation with the intended design behavior.

## Conclusion
Consistent assignment style improves readability and reduces race-related surprises.
