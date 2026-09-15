# Project Status

**Current stage:** Phase 0 — target intake and reproducibility baseline

Generation VIII decompilation is active across Sword, Shield, Brilliant Diamond, Shining Pearl, and Pokémon Legends: Arceus. This repository tracks Shield independently while preserving verified Sword/Shield relationships.

## Progress

- [x] Establish clean repository baseline
- [x] Begin exact-target intake workflow
- [ ] Record exact Shield base/update/DLC target hashes
- [ ] Document observed executable and filesystem layout
- [ ] Compare Sword/Shield only with byte/hash-backed evidence
- [ ] Map symbols, functions, and major subsystems
- [ ] Document game-data formats and resource containers
- [ ] Reconstruct the first bounded source subsystem
- [ ] Add reproducible extraction/repacking tooling as formats are verified
- [ ] Add automated reconstruction verification where practical

## Content targets

- Pokémon Shield base game
- Pokémon Shield updates/revisions
- The Isle of Armor
- The Crown Tundra

DLC is not collapsed into a generic add-on bucket; each content set is tracked independently when files, data, scripts, assets, or behavior differ.

## Validation levels

- **Unverified** — proposed or recorded but not independently checked.
- **Reference only** — sourced externally and not yet matched to the local target.
- **Observed** — confirmed directly in the selected target build or extraction.
- **Reproduced** — recreated by documented tooling or steps.
- **Matched** — reconstructed output satisfies an explicit match criterion.

## Immediate next milestone

Inventory a locally verified Shield target, then build the first observed executable/filesystem map before source reconstruction expands.
