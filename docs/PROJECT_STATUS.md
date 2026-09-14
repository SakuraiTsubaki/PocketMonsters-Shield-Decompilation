# Project Status

**Current stage:** Phase 0 — Target definition / exhaustive public-source census

This document tracks decompilation progress, target-version coverage, validation level, and the next major milestones.

The project currently has **no locally owned retail game dump**. Work therefore proceeds by exhaustive public-source research, using the Japanese release as the comparison baseline and preserving Shield-specific, regional, language, update, DLC, distribution, HOME and technical differences.

## Version inventory

| Target | Region | Language | Revision / update | Verification | Notes |
| --- | --- | --- | --- | --- | --- |
| Pocket Monsters Shield launch | JP baseline | 9 officially supported languages | launch state | Reference only | 2019-11-15 official release; exact build/hash TBD. |
| Shield updates | JP baseline | binary language identity TBD | 1.1.0 → 1.3.2 | Reference only | Official Japanese chronology recorded in `VERSIONS.md`. |
| Isle of Armor | JP baseline + all regions | multilingual | 1.2.x era | Reference only | Major independent DLC workstream. |
| Crown Tundra | JP baseline + all regions | multilingual | 1.3.x era | Reference only | Major independent DLC workstream. |

## Active exhaustive-source work

- Japanese Sword/Shield official corpus is being reclassified for Shield applicability rather than inherited from Sword.
- Shield-specific version differences are an independent source family.
- Shared Project Pokémon SWSH archive (215 current category records) must be classified as Shield/Sword/both/version-dependent.
- pkNX, PKHeX, CaptureSight, RaidFinder, RNG tools, ExeFS hook projects and asset-format tooling are indexed as external research sources.
- regional/language storefronts, distributions, Wild Area News, competitions, HOME, packaging and archived/deleted material are separate workstreams.

## Technical progress

- [ ] Establish authoritative version/revision inventory — **in progress**
- [ ] Document executable and section layout
- [ ] Map symbols, functions, and major subsystems
- [ ] Document game-data formats and resource containers — **public source mapping started**
- [ ] Reconstruct scripts, events, and behavior
- [ ] Reconstruct asset pipelines and metadata — **format/tool source mapping started**
- [ ] Add reproducible extraction/repacking tooling
- [ ] Add automated verification where practical

## Active research material

- `docs/research/PUBLIC_SOURCE_INDEX.md`
- `docs/research/SOURCE_COVERAGE_TRACKER.md`
- `docs/VERSIONS.md`
- `manifests/source-coverage.json`

## Validation levels

- **Unverified** — proposed or external technical claim not independently checked against the target.
- **Observed** — confirmed directly in a target build or extracted target data.
- **Reproduced** — behavior/data can be recreated with documented steps.
- **Matched** — reconstructed output is verified against the intended target.
- **Reference only** — primary/secondary public evidence exists but target identity/hashes are unavailable.

## Immediate next milestones

1. Build the complete Shield-specific Japanese official page ledger, including DLC and off-index official pages.
2. Independently classify all 215 Project Pokémon SWSH archive entries for Shield applicability.
3. Enumerate every Shield version-exclusive Pokémon/Gym/raid/story/data difference.
4. Recursively inventory pkNX and PKHeX Shield/SWSH schemas, save blocks and paths.
5. Expand all official regional/language sources against the Japanese baseline.
6. Build complete Wild Area News/BCAT and competition chronologies with revision tracking.
7. Catalogue packaging, cartridge revisions, identifiers, bugs, unused/pre-release and archived material.

Update this file whenever a meaningful milestone changes.
