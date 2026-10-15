# Introduction to the RTL Workflow

A digital design is usually described using RTL, tested through simulation, and then passed to synthesis. This section outlines the stages and the role of each tool.

### Simulation cycle
- Design: describe the intended logic in Verilog.
- Test: apply input sequences through a testbench.
- Compile and run: use a simulator to evaluate the design.
- Inspect: review signal changes and timing in a waveform viewer.

### Why use a testbench?
A testbench automates input generation and makes it easier to repeat tests. It should cover ordinary cases as well as boundary conditions.

### Synthesis introduction
Synthesis interprets the RTL and maps its behavior into logic elements. The resulting netlist can be inspected to see how the design is represented as gates and registers.


