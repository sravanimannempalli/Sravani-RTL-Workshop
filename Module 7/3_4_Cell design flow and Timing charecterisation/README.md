# 3 & 4 — Standard-Cell Design Flow and Timing Characterization

## Overview
Standard-cell development connects transistor-level design, layout geometry, verification, and timing models used by digital implementation tools.

## Typical sequence
1. Define the cell's intended logic and electrical behavior.
2. Design the transistor-level circuit.
3. Create the physical layout.
4. Check layout rules and connectivity.
5. Characterize delay and transition behavior under defined conditions.
6. Package the required physical and timing views for use by design tools.

## Timing concepts
Propagation delay describes the time between an input transition and the corresponding output response. Transition time describes how quickly a signal changes between defined voltage thresholds. Characterized values depend on input slew, output load, and operating corner.

## Conclusion
Accurate cell views and timing models help synthesis and timing analysis make realistic implementation decisions.
