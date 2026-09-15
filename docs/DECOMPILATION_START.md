# Decompilation Start

Active decompilation begins with exact-target intake and reproducibility. This repository is one of the Generation VIII reconstruction targets and is not treated as a derivative of the Sword repository.

## Phase 0 — target intake

1. Keep retail game images, decrypted package archives, console keys, and complete redistributed game binaries outside Git.
2. Inventory the actual locally obtained extraction by relative path, size, and SHA-256.
3. Record the exact base-game/update/DLC revision before interpreting code or data.
4. Treat The Isle of Armor and The Crown Tundra as distinct content targets when their files or behavior differ.

## Phase 1 — executable and filesystem map

Map only structures directly observed in the selected Shield target: executable files, sections, build identifiers, imports/relocations where present, RomFS paths, containers, and resource tables. Do not copy names or layouts from Sword merely because the titles are paired.

## Phase 2 — bounded source reconstruction

Choose a small subsystem with a stable input range and an explicit verification method. Reconstructed source is added only when there is real evidence-backed work to commit.

## Verification

Use `Unverified`, `Reference only`, `Observed`, `Reproduced`, and `Matched` consistently. Pairwise Sword/Shield deduplication requires byte/hash evidence; visual or behavioral similarity alone is not sufficient.
