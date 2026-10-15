# Module 9 — Cell Views, Timing Tables, and Physical Design Integration

## Overview
The final module brings together physical cell information, technology data, timing models, and layout-tool concepts used in an RTL-to-silicon workflow.

## Topics
- Cell layout and pin definitions
- LEF and Liberty file roles
- Timing lookup tables
- Routing grids and tracks
- Technology and cell-library integration
- Reviewing layout and flow outputs

## LEF and Liberty
LEF typically describes physical abstracts such as cell dimensions, pins, and routing obstructions. Liberty describes logical function and timing/power characteristics. They serve different purposes and are both important to implementation tools.

## Timing Tables
Cell timing can be characterized across combinations of input transition and output load. The resulting tables support timing estimation; their values depend on the characterized library and corner.

## Physical Integration
Routing tracks and technology layers guide how interconnect is represented. Correct technology and library setup is necessary for physical-design tools to interpret cells and routes properly.

## Final Reflection
RTL design, synthesis, cell libraries, layout, and timing analysis form a connected flow. Reliable results require correct inputs, documented tool settings, and review of the reports generated at each stage.

> Add your own verified screenshots, commands, and results before treating this module as a completed lab record.
