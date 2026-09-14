# Documentation Hub

This directory is the central documentation portal for the decompilation project. The current phase is a **ROM-less exhaustive public-source census**, using the Japanese release as the comparison baseline while preserving Shield-specific and all-region differences.

## Quick links

| Document | Purpose |
| --- | --- |
| [Project Status](PROJECT_STATUS.md) | Current stage, target coverage and next milestones |
| [Version Coverage](VERSIONS.md) | Launch/update/revision inventory |
| [Public Source Index](research/PUBLIC_SOURCE_INDEX.md) | Living Shield public-source ledger |
| [Exhaustive Source Coverage](research/SOURCE_COVERAGE_TRACKER.md) | Per-source-family completion state |
| [Roadmap](ROADMAP.md) | Project phases |
| [Research Guide](RESEARCH_GUIDE.md) | Evidence and research-recording practices |
| [Verification Guide](VERIFICATION.md) | Unverified/Observed/Reproduced/Matched standards |
| [Repository Structure](REPOSITORY_STRUCTURE.md) | Intended source/data/assets/tools/manifests layout |
| [Project Standards](PROJECT_STANDARDS.md) | Naming and provenance rules |
| [Asset Workflow](ASSET_WORKFLOW.md) | Asset handling and deduplication rules |
| [Manifest Guide](../manifests/README.md) | Machine-readable inventories |
| [Contributing](../CONTRIBUTING.md) | Contribution/commit guidance |

## Recommended research flow

1. Check `research/SOURCE_COVERAGE_TRACKER.md` so a seed list is never mistaken for completed research.
2. Identify target version/update state in `VERSIONS.md`.
3. Register newly discovered primary/technical sources in `research/PUBLIC_SOURCE_INDEX.md` even before full interpretation.
4. Keep Shield applicability separate from Sword when a shared SWSH source is used.
5. Record methods/evidence according to `RESEARCH_GUIDE.md`.
6. Add source/data/assets only when real material exists; do not create decorative empty trees.
7. Apply `VERIFICATION.md` levels and update `PROJECT_STATUS.md` when milestones change.

## Documentation rules

- Representative samples do not satisfy an exhaustive source family.
- Japanese material is the baseline, not a reason to erase regional differences.
- Region, language, version, revision, DLC state and binary identity are separate concepts.
- Distinguish public-source observation from direct retail-target verification.
- Use `TBD`, `unknown` or `null` instead of inventing missing data.
- Preserve provenance sufficient for another researcher to reproduce or challenge a finding.
- Keep retail game images, decrypted game images and console keys out of the repository.
