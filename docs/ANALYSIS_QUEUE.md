# Active Analysis Queue

This queue defines the first evidence-backed work for the Pokémon Shield decompilation. It is intentionally ordered so source reconstruction does not outrun target verification.

## 0. Target identity

- [ ] Hash the exact local base-game extraction.
- [ ] Hash the exact local update extraction.
- [ ] Record whether The Isle of Armor and The Crown Tundra content is present.
- [ ] Record observed build identifiers from the selected executable target.
- [ ] Promote matching entries in `manifests/targets.json` from `reference_only` only when local evidence supports it.

## 1. ExeFS map

- [ ] Enumerate every observed ExeFS path.
- [ ] Record file sizes and SHA-256 values.
- [ ] Identify executable/container formats from file signatures and structure.
- [ ] Record sections, offsets, imports/relocations, and build identifiers where directly observable.
- [ ] Create a version-bound executable map before assigning semantic symbol names.

## 2. RomFS map

- [ ] Enumerate the complete observed RomFS tree.
- [ ] Group files by extension/signature/container without assuming semantics from names alone.
- [ ] Record counts, hashes, and path-level differences between base and update data.
- [ ] Separate Expansion Pass content from base-game content when evidence shows a distinct source or condition.

## 3. Sword / Shield pairwise comparison

Comparison is secondary to independent mapping.

- [ ] Compare verified Shield files against the corresponding verified Sword target by path, size, and SHA-256.
- [ ] Classify entries as identical, Shield-specific, Sword-specific, or differing.
- [ ] Deduplicate project representations only when byte/hash identity is demonstrated.
- [ ] Keep version-exclusive encounters, trainers, text, events, assets, and executable differences explicit.

## 4. First bounded reconstruction candidates

Choose only after the executable/data map supports the choice. Candidate classes include:

1. a small deterministic table parser or lookup routine;
2. a self-contained resource/container reader;
3. a version-exclusive data table that can be compared against Sword;
4. a script/event structure with a reproducible decode/encode test.

Do not begin with a large gameplay subsystem merely because its high-level behavior is known.

## 5. Verification gates

A reconstructed component advances through:

`Unverified -> Observed -> Reproduced -> Matched`

`Matched` requires an explicit criterion such as byte-identical regenerated data, instruction-equivalent output under a defined compiler/toolchain condition, or another documented exact comparison appropriate to the component.
