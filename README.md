# Pocket Monsters Shield — Decompilation

![Status](https://img.shields.io/badge/status-public_source_census-blue)
![Project](https://img.shields.io/badge/project-decompilation-blue)
![Retail dump](https://img.shields.io/badge/local_retail_dump-not_available-orange)
![ROMs](https://img.shields.io/badge/ROM_binaries-not_included-success)

Decompilation and source-reconstruction project for **Pokémon Shield / ポケットモンスター シールド**.

## 🎯 Goals

- Reconstruct game code and data into readable, editable source form as public evidence permits.
- Exhaustively catalogue public official, archival, reverse-engineering, data-format, distribution, network, patch, regional and community research sources.
- Use the **Japanese release as the comparison baseline** while preserving every regional/language/version/revision difference independently.
- Keep Shield separate from Sword even when sources cover both versions.
- Treat The Isle of Armor and The Crown Tundra as major Shield-linked workstreams.
- Document executable structures, data formats, scripts, assets, saves, network-delivered data and version differences.
- Keep provenance, verification status and reproducibility explicit.

## 🚧 Current status

**Phase 0 — Target definition / exhaustive public-source census.**

There is currently **no locally owned retail game dump** for this project. Research therefore starts from publicly accessible evidence. Unknown binary identities, hashes, cartridge revisions and internal fields are left unresolved rather than guessed.

Current work includes:

- official Japanese launch/update/DLC chronology;
- all-region and all-language official-source mapping;
- Shield-specific version differences;
- distributions, Wild Area News, competitions and Pokémon HOME;
- pkNX / PKHeX / runtime / RNG / asset-format research;
- Project Pokémon SWSH event/archive classification;
- packaging, bugs, unused/pre-release and archived material.

See [Project status](docs/PROJECT_STATUS.md) and [Exhaustive source coverage](docs/research/SOURCE_COVERAGE_TRACKER.md).

## 🗂️ Planned scope

- Code and executable analysis
- Game data structures
- Scripts and event data
- Graphics, models, animations, UI and asset metadata
- Audio and resource formats
- Maps and world data
- Pokémon / moves / items / abilities / evolution / encounters / raids / trainers
- Save data and HOME interoperability
- Wild Area News / BCAT / network-delivered event data
- Region / language / patch / revision / DLC comparison
- Tools, notes, manifests and verification data

## 📌 Repository policy

Retail ROM/game images, redistributed game binaries and console keys are **not included**. The repository stores research, reconstructed source, tools, metadata, manifests, independently redistributable material and documentation subject to provenance/license review.

## 🧭 Roadmap

- [ ] Exhaust public-source families and establish authoritative version/revision inventory
- [ ] Map executable and data structures from corroborated public technical evidence
- [ ] Begin source/data reconstruction where evidence supports it
- [ ] Document assets, scripts, formats and version-specific behavior
- [ ] Add reproducible verification workflows when target evidence becomes available

## 📚 Documentation

| Document | Purpose |
| --- | --- |
| [Project status](docs/PROJECT_STATUS.md) | Current stage, coverage and next milestones |
| [Version coverage](docs/VERSIONS.md) | Launch/update/revision inventory |
| [Public source index](docs/research/PUBLIC_SOURCE_INDEX.md) | Living Shield public-source ledger |
| [Exhaustive source coverage](docs/research/SOURCE_COVERAGE_TRACKER.md) | Per-source-family completion state |
| [Roadmap](docs/ROADMAP.md) | Long-term project phases |
| [Research guide](docs/RESEARCH_GUIDE.md) | Evidence and research-recording workflow |
| [Verification guide](docs/VERIFICATION.md) | Unverified/Observed/Reproduced/Matched standards |
| [Repository structure](docs/REPOSITORY_STRUCTURE.md) | Intended source/data/asset/tooling layout |
| [Documentation hub](docs/README.md) | Documentation entry point |

## 🧱 Repository structure

The existing repository standards remain authoritative. New directories are created only when real research/reconstruction material exists; empty trees are not added for appearance. Platform/game structure follows verified Shield evidence rather than another generation's layout.

## 🔬 Research and verification

Every material claim should identify game/version/region/language where relevant, retain source provenance, and separate public-source observation from direct retail-target verification. Shared Sword/Shield evidence must be reclassified for Shield applicability rather than copied blindly.

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution rules, evidence expectations and commit guidance.
