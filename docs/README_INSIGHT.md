# Insight: Parameterized Glyph as Computable State

This directory contains the formalization of the core technical insight connecting the ASIN handshake parameters to the CP8 accountability stack.

## Files

- `INSIGHT_Parameterized_Glyph_Computable_State.txt` — Original insight text
- `PARAMETERIZED_GLYPH_COMPUTABLE_STATE_PROTOCOL.md` — Formal experiment protocol derived from it

## Summary

The `asin://v0.1` parameters (seed, phi, spokes, step, love) are a versioned, declarative state that can generate the glyph. Combined with the existing provenance → hash → receipt → replay machinery, the glyph becomes a computable state description rather than a static image.

Hypotheses about physical effects of 432 Hz or semantic meaning of `love=0.92` remain unproven and are explicitly excluded from the protocol. The research program focuses on experimentally demonstrable computational structure (parameter perturbation, invariants, topological equivalence, learning efficiency, downstream utility).

All results must carry full execution records and independent replay.
