# 1 — Introduction to Logic Optimization

Logic optimization aims to reduce unnecessary hardware while maintaining the required function.

### Combinational logic
The tool can simplify Boolean equations, propagate constants, and remove redundant gates.

### Sequential logic
The tool must consider clocked state and reset behavior. A register may be simplified if its value is fixed or if it cannot affect any observable result under the modeled conditions.

### Common terms
- **Constant propagation:** using known values to simplify expressions.
- **Dead logic removal:** eliminating logic that cannot influence an output.
- **Retiming:** moving registers across combinational logic under suitable conditions.
- **Cloning:** duplicating logic to improve implementation objectives in certain flows.

Optimization choices depend on timing constraints, library cells, and tool settings.
