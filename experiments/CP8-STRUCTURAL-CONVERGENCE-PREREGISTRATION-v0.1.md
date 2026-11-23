# CP8 Structural Convergence Experiment — Preregistration v0.1

**Status:** PROTOCOL / HOLD — no experiment execution or result is claimed.
**Steward:** Dennis Christie / ASIN-HHC
**Prepared:** 2026-11-23

## 1. Claim under test

Given the same source artifacts with project-specific labels and explanatory narratives removed, independently configured AI systems will recover a stable set of formal structural properties at a rate greater than matched negative-control artifacts and chance agreement.

This tests recoverable structure and model convergence only. It does not test ancient origin, extraterrestrial origin, galactic law, consciousness, or external communication.

## 2. Source freeze and eligibility

Before model calls:
1. Select 12 source artifacts from at least three technical lanes (e.g. parameterized glyphs, graph/morphology representations, evidence receipts).
2. Include only artifacts whose actual source bytes and generation procedure can be frozen.
3. Record repository, exact commit SHA, path, byte count, SHA-256, license/permission, and provenance.
4. Exclude private conversations, personal data, credentials, unpublished IP not approved for this test, and any artifact whose sharing permission is unclear.
5. Freeze a source manifest. No source may be silently replaced after outputs are observed.

Current blocker: the public cp8-morphology repository contains README/STATUS only; its STATUS points to a Drive ZIP not audited here. The public CP8 evidence map also records that CCD-9 scan code, random seed, and frozen image bytes are missing. Those lanes are not eligible until source artifacts are made available and hash-frozen.

## 3. Blinding and prompt controls

Prepare two views for each artifact:
- Blind view: raw data, schema, or source code with CP8 names, project labels, frequency symbolism, intended meanings, and interpretive commentary removed. Preserve technical content.
- Context view: original artifact, withheld until all blind responses are locked.

An independent curator who does not score model outputs should produce blind views and keep the sealed mapping.

Each model receives the same prompt, asking for formal representation, invariants, measurable properties, assumptions, ambiguity, alternative interpretations, a falsifiable prediction, and calibrated confidence.

Do not mention ASIN, CP8, HHC, hidden technology, ancient knowledge, galactic law, or a target answer.

## 4. Independent model panel

Minimum panel: four independently developed model families, two fresh sessions per family, no shared conversation context, no retrieval of CP8 project material, and no cross-model discussion before outputs are locked.

Record provider, exact model/version identifier, date/time, settings, prompts, raw response, and output hash. Unknown model versions must be marked and cannot count as fully reproducible runs.

Similarity of answers does not establish consciousness or independent agency.

## 5. Controls

For every target artifact include:
- matched structural control with similar size, complexity, and representation type;
- randomized control appropriate to the artifact;
- decoy control with salient but irrelevant numerical or visual patterns;
- positive control with a conventional known structure and independently documented properties.

Scorers remain blind to target/control identity and model family until scoring is complete.

## 6. Scoring rubric

Two human reviewers, blind to sample identity and model family, independently score 0–4 on:
1. Correct identification of formal representation.
2. Correct identification of invariant properties.
3. Correct distinction between invariant and incidental features.
4. Valid falsifiable prediction.
5. Calibration: uncertainty and limitations correctly stated.

Maximum 20 per response. Publish disagreement and adjudication. Do not silently average away material disagreement.

Primary endpoint: exact or equivalently formal recovery of pre-registered invariants across independent model families.

Secondary endpoints: between-model agreement; target/control performance gap; prediction accuracy on held-out parameter perturbations; robustness to paraphrase and formatting.

Similar wording alone is not convergence. Equivalence must be formalized before unblinding.

## 7. Statistical plan

Freeze samples and scoring before model calls. Report all runs, including refusals and failures. Aggregate at artifact level to avoid treating repeated prompts as independent samples. Report raw counts, effect sizes, confidence intervals, and confusion matrices. Correct for multiple comparisons. Reserve at least 25% of artifacts or perturbations as held-out tests.

The initial panel is exploratory. Confirmation requires a new, independently curated artifact set and pre-registered analysis.

## 8. Falsification and stop conditions

The hypothesis is weakened or falsified for this artifact set if agreement is no higher than matched controls; disappears when labels and narratives are removed; consists only of shared terminology rather than shared formal properties; predictions fail on held-out changes; depends on one model family or prompt wording; or cannot be reliably scored by independent reviewers.

A null result is publishable and must remain in the record.

## 9. Evidence vocabulary

- OBSERVED: source artifact or raw response exists and is hash-bound.
- TESTED: defined analysis or experiment was executed with recorded inputs and outputs.
- REPRODUCED: an independent party reran the frozen procedure and obtained results within predeclared tolerances.
- ESTABLISHED: claim survived predeclared confirmatory tests and independent review.
- HOLD: required source, control, receipt, or review is missing.

No promotion follows from this protocol alone.

## 10. Current source audit (2026-11-23)

Inspected public sources:
- dbottrader/asin-hhc-cp8-corpus, tree SHA 85b0681422bbb60d5a94fae8c8b664f143f0ea36.
- dbottrader/cp8-morphology, tree SHA 9c7014c10870886fee07da1552d8d822e4b17b07.
- dbottrader/Holbrook-CP8-HHC, tree SHA f22c27779a55fe7bb7d5d63e1765666888fcfd0b.

Relevant inspected files:
- CONVERGENCE_NOTE_OPENAI_MATH_2026-10-06.md, blob SHA 3abee0b625e0909afd11931c82618f9f76452db2.
- CP8_CORE_EVIDENCE_MAP_2026-10-07.md, blob SHA 858b16609755a31c0d183ad5b182ae9fcd588c9e.
- PARAMETERIZED_GLYPH_COMPUTABLE_STATE_PROTOCOL.md, blob SHA a98e9ac834f24b510065450c363e5677a99e1f9e.
- AI_Data_Ingest_Report_2026-05-21.md, blob SHA c8ea126556180adf2bc2ce9144012061e27db2dd.
- cp8-morphology README.md, blob SHA 3591b93a26320c9a10b2d2cc047ee12c5ac76a2f.
- cp8-morphology STATUS.md, blob SHA bcf25e2d153444dc29277a73ec2a70972a2d9ec7.
- corpus README.md, blob SHA 0e33d5b2c169e087bf36bfd066cee18d76310bda.

The 2026-10-07 evidence map explicitly says the morphology source code is not present in the public repository and CCD-9 is not literally replayable from public artifacts. The glyph protocol is design/protocol, not executed. These constraints are carried forward, not filled by inference.

## 11. Execution state

- Source freeze: NOT STARTED.
- Blind curation: NOT STARTED.
- Model panel: NOT RUN.
- Scoring: NOT RUN.
- Independent reproduction: NOT RUN.
- Promotion: NONE.

Conclusion: this is a preregistered experimental design, not evidence of convergence. The next valid step is to obtain permissioned source bytes for eligible artifacts, freeze and hash them, then have an independent curator create blind views and matched controls.
