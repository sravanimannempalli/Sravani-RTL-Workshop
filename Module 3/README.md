# Module 3 — Logic Optimization

## Overview
This module examines how synthesis tools simplify combinational and sequential logic while preserving externally observable behavior.

## Topics
- Boolean expression simplification
- Constant propagation
- Removal of redundant or unused logic
- Sequential optimization
- Register and state-related transformations
- Comparing RTL and optimized netlists

## Combinational Optimization
Combinational logic depends only on current inputs. Equivalent Boolean expressions may be implemented using different gate structures, and synthesis attempts to find an implementation suitable for the target library and constraints.

## Sequential Optimization
Sequential circuits contain state elements. Their optimization must preserve relevant state transitions and output behavior. Constant registers or unreachable logic may be simplified when the tool can prove that they do not affect required behavior.

## Evaluation Method
Use the same functional checks before and after synthesis. Inspect netlist changes and relate each change to the RTL and the design's observable outputs.

## Key Takeaway
A smaller-looking netlist is not sufficient evidence of correctness; functional equivalence and design requirements remain essential.
