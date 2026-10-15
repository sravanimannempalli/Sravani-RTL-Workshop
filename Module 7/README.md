# Module 7 — Floorplanning, Power Planning, and Placement

## Overview
This module explores early physical-design decisions and how the synthesized netlist is arranged within a chip's core area.

## Topics
- Die and core dimensions
- Utilization and aspect ratio
- Pin placement
- Power distribution planning
- Standard-cell placement
- Library binding
- Placement optimization and buffers

## Floorplanning
Floorplanning defines the approximate physical area and organizes the design for implementation. Utilization, aspect ratio, I/O locations, and macro placement can influence congestion and routing feasibility.

## Power Planning
The power network distributes supply and ground to cells. Its structure must satisfy the process and flow requirements.

## Placement
Placement assigns locations to standard cells. Optimization may adjust placement or insert buffers to address timing, fanout, and electrical constraints.

## Key Takeaway
Physical design decisions interact: area, congestion, timing, and power should be considered together rather than in isolation.
