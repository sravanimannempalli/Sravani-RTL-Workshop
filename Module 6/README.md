# Module 6 — Introduction to SoC Design and OpenLane

## Overview
This module moves from RTL concepts toward the physical implementation of a chip. It introduces the software-to-hardware path, system-on-chip organization, and the OpenLane RTL-to-GDSII flow.

## Topics
- From software descriptions to digital hardware
- Basic RISC-V and SoC context
- Foundries, macros, and standard cells
- Open-source EDA tools
- OpenLane configuration and flow stages
- Design files, configuration parameters, and generated reports

## RTL-to-GDSII at a glance
A typical implementation flow includes RTL preparation, synthesis, floorplanning, placement, clock-tree synthesis where applicable, routing, and physical verification. Exact stages depend on the tool version and configuration.

## OpenLane Setup
A design configuration identifies the top module, source files, constraints, target platform, and other flow parameters. Reports and intermediate files help diagnose problems at each stage.

## Key Takeaway
Physical design is a sequence of linked steps. A successful stage does not automatically guarantee that the entire flow completed or that all design checks passed.
