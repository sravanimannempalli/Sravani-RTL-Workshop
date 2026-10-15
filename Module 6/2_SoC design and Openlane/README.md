# 2 — SoC Design and the OpenLane Flow

## Objective
Understand the major stages used to convert a digital design into a physical layout.

## Flow outline
1. RTL and constraints are prepared.
2. Logic synthesis generates a mapped netlist.
3. Floorplanning establishes die/core dimensions and I/O locations.
4. Power distribution is planned.
5. Standard cells are placed and optimized.
6. Clock and signal routing are performed as required by the flow.
7. Design-rule and timing checks are reviewed.
8. Layout data is exported in the required format.

## Why configuration matters
Incorrect top-module names, missing source files, unsupported parameters, or incorrect constraints can stop a run or produce an invalid result.

## Conclusion
Understanding the purpose of each stage makes OpenLane reports easier to navigate and debug.
