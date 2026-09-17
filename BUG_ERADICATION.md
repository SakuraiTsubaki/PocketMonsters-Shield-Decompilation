# Bug Eradication Program

## Goal

Drive the repository toward **zero known reproducible unintended defects** for the selected Pokémon Shield target revision while preserving intended game rules, content, version differences, and patch-era behavior as documented evidence.

This program covers crashes, hangs, softlocks, progression blockers, save/data corruption, battle-logic defects, AI defects, invalid data, script/event errors, collision and map errors, graphics/UI/display errors, audio errors, localization/text errors, online/local communication defects, DLC interactions, performance defects, resource leaks, update regressions, and other reproducible unintended behavior.

## Target identity gate

No binary-specific fix is considered verified until `config/target.json` identifies the exact release/region/revision and cryptographic hashes of the locally supplied legal dump or extracted target. ROM/installable-package binaries are never committed.

## Evidence classes

- **Confirmed**: reproduced on the exact target or proven from extracted code/data with sufficient evidence.
- **Probable**: strong code/data evidence but reproduction is incomplete.
- **Reported**: externally documented report awaiting local reproduction.
- **Not a bug**: intended behavior, unsupported configuration, user/environment error, or disproven report.

## Severity

- **S0 Critical** — save corruption, unrecoverable progression loss, deterministic fatal crash affecting normal play.
- **S1 High** — softlock, major progression failure, severe battle/system logic break, frequent crash.
- **S2 Medium** — incorrect mechanics/data/event behavior with meaningful gameplay impact.
- **S3 Low** — visual/audio/text/UI/collision issues with limited gameplay impact.
- **S4 Cosmetic** — presentation-only defect with no functional impact.

## Required lifecycle

Every defect must pass through discovery/source citation, target/revision assignment, reproduction, root-cause analysis, minimal fix, non-ROM patch output, positive and negative regression tests, version/DLC compatibility checks, and final `verified-fixed` status only after all required tests pass.

## Shield-specific version axes

Track base game, The Isle of Armor, The Crown Tundra, offline/local/online behavior, original release versus each supported update revision, region/language differences, and Shield-only versus Sword-shared code/data behavior separately when applicable.

## Repository placement

- `manifests/bug-registry.json`: authoritative machine-readable defect index.
- `analysis/bugs/`: reproduction notes and root-cause reports.
- `patches/bugs/`: patch material, diffs, address/symbol maps.
- `logs/bugs/`: execution and regression logs.
- `artifacts/bugs/`: retained non-ROM outputs and evidence.
- `tools/`: validators and automation.

## Completion rule

A revision is considered clean only when every known registry item is either `verified-fixed` or `not-a-bug`, all automated validations pass, and no unresolved report or regression remains for that revision.
