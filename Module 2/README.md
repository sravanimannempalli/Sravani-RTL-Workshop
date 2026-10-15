# Module 2 — Cell Libraries, Hierarchy, and Flip-Flops

## Overview
This module explores standard-cell libraries, hierarchical versus flattened synthesis, and sequential RTL coding styles. It connects RTL descriptions to the cells that may implement them.

## Topics Covered
- Reading library information and identifying cell variants
- Process, voltage, and temperature (PVT) corners
- Hierarchical and flat synthesis
- Synchronous reset and asynchronous reset behavior
- Flip-flop inference and synthesis checks

## Library Walkthrough
A Liberty file can contain functional, timing, and power information for standard cells. Different drive strengths or cell variants can offer different area and delay characteristics. PVT conditions affect the values reported by the library.

## Hierarchical vs. Flat Synthesis
Hierarchical synthesis preserves module boundaries for part of the flow, while flattening allows logic across hierarchy boundaries to be optimized together. The best choice depends on design goals and flow constraints.

## Flip-Flop Coding
- A synchronous reset is sampled with the active clock edge.
- An asynchronous reset can affect the register independently of the clock, according to its sensitivity and reset condition.
- Incomplete or inconsistent sequential descriptions can infer unintended hardware.

## Key Takeaways
Use clear sequential coding styles, verify reset behavior in simulation, and check synthesis output to confirm that the expected registers and logic were inferred.
