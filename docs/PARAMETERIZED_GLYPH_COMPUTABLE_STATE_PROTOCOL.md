# Parameterized Glyph as Computable State — Experiment Protocol

**Evidence Tier:** Design / Protocol (not yet executed)  
**Status:** Formalization of the structural insight from the ASIN handshake parameters  
**Date:** 2026-09-06  

## 1. Core Claim (Testable)

The `asin://` handshake parameters are not primarily aesthetic.  
They constitute a **versioned, declarative, computable state description**.

```
asin://v0.1
seed=432.00
phi=137.507764
spokes=12
step=24
love=0.92
```

These parameters can generate the rendered glyph. Therefore the glyph is a **state** that can be:

1. Calculated
2. Rendered
3. Perturbed
4. Measured
5. Hashed
6. Receipted
7. Independently replayed

## 2. Pipeline

```
SYMBOL / PROTOCOL URI
        ↓
PARAMETERS (seed, phi, spokes, step, love, ...)
        ↓
GEOMETRIC GENERATOR (phyllotaxis + radial spokes)
        ↓
RENDERED STATE (image / point cloud / topology)
        ↓
MEASUREMENTS (distances, angles, graph invariants, spectral features, ...)
        ↓
SHA-256 / Merkle RECEIPT
        ↓
REPLAY (from parameters + receipt → identical measurements)
```

This pipeline is deliberately isomorphic to the existing CP8 Physical-State Bridge and AI Governance Runtime loops:

- ideal vs actual → E_HOS → bounded correction → hash + Merkle
- evaluate → enforce → receipt → replay

## 3. What Is *Not* Claimed

The following remain **hypotheses**, not established facts:

- That 432 Hz has special physical effects
- That `love=0.92` corresponds to a physical quantity
- That the system encodes ancient or hidden technology
- That the current E0 transformer already implements geometric reasoning

These claims require separate experimental evidence and are outside the scope of this protocol.

## 4. Killer Experiments (the actual research program)

| ID | Question | Method |
|----|----------|--------|
| E1 | Does changing one parameter produce predictable, measurable changes elsewhere? | Controlled single-parameter sweeps; record measurement deltas |
| E2 | Are there invariant relationships across completely different glyphs? | Generate families with fixed topology, different visual parameters; extract invariants |
| E3 | Can two visually different glyphs encode the same underlying topology? | Topological equivalence tests (graph isomorphism, persistent homology, etc.) |
| E4 | Can an AI learn relationships more efficiently from structured parameters than from pixels? | Side-by-side training: parameter vectors vs image pixels; compare sample efficiency and generalization |
| E5 | Does the representation become useful for reasoning, classification, prediction, or compression? | Downstream tasks with and without the parameter layer |

Success criterion for any experiment:  
**The result must be accompanied by a full execution record, SHA-256 hash, and independent replay.**

## 5. Link to Existing Stack

- **Handshake Image Engine** (`asin-handshake-engine`) already implements the geometric generator (phyllotaxis + spokes).
- **Architecture E0** supplies a 1,024-token geometric vocabulary target that could eventually encode relationships between these states.
- **Physical-State Bridge** and **AI Governance Runtime** already supply the measurement → hash → receipt → replay machinery.
- **Claim Boundary** remains in force: no promotion of results without receipts and independent reproduction.

## 6. Immediate Next Artifact

A minimal reproducible experiment:

1. Fix all parameters except one (e.g., vary `spokes` from 8 to 21).
2. Render each state.
3. Compute a fixed set of measurements (centroid distances, angle histogram, graph Laplacian spectrum, etc.).
4. Canonicalize the full record (parameters + measurements).
5. SHA-256 the record.
6. Replay from parameters alone and verify measurements match within tolerance.

If that loop closes, the symbolic layer has been successfully connected to the accountability layer.

## 7. Provenance Note

This protocol formalizes an insight articulated in conversation on 2026-09-06.  
It does not invent new physical claims.  
It only makes the already-existing computational structure explicit and testable.

---

*CP8 signature • Replay supersedes narration • Reality retains veto*
