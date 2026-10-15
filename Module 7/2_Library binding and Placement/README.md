# 2 — Library Binding and Placement

## Objective
Study how logical cells are associated with technology-library cells and physically placed.

## Library binding
Synthesis maps logic to cells available in the target library. The physical-design flow uses technology and cell information to understand cell dimensions, pins, and implementation requirements.

## Placement
Placement assigns locations to cells while considering connectivity, timing, density, and design constraints. Buffers may be inserted or cells moved to improve implementation quality.

## What to inspect
- Whether the intended technology library is loaded.
- Whether the design contains unmapped or unsupported cells.
- Placement density and congestion indicators.
- Optimization messages and timing reports.
- The placement database or layout view, if available.

## Conclusion
Correct library setup and valid placement are prerequisites for successful downstream physical implementation.
