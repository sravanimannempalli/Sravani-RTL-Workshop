# Introduction to Yosys and Logic Synthesis

Yosys is an open-source synthesis framework used to process RTL and produce a gate-level or technology-mapped netlist.

## Main stages
1. Read the RTL source.
2. Check and elaborate the design hierarchy.
3. Run synthesis transformations and logic optimization.
4. Map the logic to a selected cell library when configured.
5. Review the resulting netlist or a graphical representation.

## Why libraries matter
A standard-cell library describes available cells and their characteristics. Mapping depends on which cells exist in the target library and on the synthesis constraints.

## Points to examine
- Which module is selected as the top module?
- Are all intended source files included?
- Does the synthesized logic preserve the RTL function?
- Are any signals or logic optimized away?

Synthesis reports should be interpreted alongside functional simulation; a netlist's appearance alone does not prove correctness.
