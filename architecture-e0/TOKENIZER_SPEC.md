# CP8 Tokenizer Specification — E0

## Target

The available CP8 architecture documentation specifies a vocabulary size of **1,024 tokens** for structured geometric or glyph sequences.

## Current state

A complete canonical mapping from token IDs `0..1023` to glyphs, operators, delimiters, structural markers, and reserved tokens was not located in the available artifacts. Therefore this release does **not** include a tokenizer implementation or fabricated vocabulary.

## Minimum requirements for promotion

A canonical tokenizer release must define:

1. Stable integer ID for every token.
2. Unicode normalization policy.
3. Reserved special tokens, including BOS, EOS, and PAD.
4. Unknown-token behavior.
5. Serialization format and version.
6. Round-trip encode/decode tests.
7. Collision and ambiguity tests.
8. SHA-256 hash of the canonical vocabulary.
9. Compatibility rules for future vocabulary revisions.
10. Provenance for every symbol family.

Until those requirements are met, generated reference weights are architecture tests only and cannot represent the intended CP8 symbolic language.
