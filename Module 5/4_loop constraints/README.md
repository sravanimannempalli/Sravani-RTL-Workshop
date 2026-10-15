# 4 — Loops and Generate Constructs

## Objective
Distinguish between procedural repetition and elaboration-time hardware generation in Verilog.

## Procedural loops
`for`, `while`, and related constructs can repeat procedural statements during simulation or synthesis, subject to the language rules and tool support. Synthesizable loops are generally expected to have bounds that the tool can determine.

## Generate constructs
`generate` with constructs such as `for` and `if` can instantiate repeated modules or hardware structures during elaboration.

## Design checks
- Confirm loop bounds and termination.
- Ensure generated instance names and parameters are valid.
- Check the elaborated hierarchy.
- Review synthesis results to see what hardware was created.

## Conclusion
Loops describe repetition in code, but the resulting hardware depends on where and how the construct is used.
