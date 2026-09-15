# Pocket Monsters Shield — Decompilation

![Status](https://img.shields.io/badge/status-phase_0_intake-yellow)
![Project](https://img.shields.io/badge/project-decompilation-blue)
![ROMs](https://img.shields.io/badge/ROM_binaries-not_included-success)

Decompilation and source-reconstruction project for **Pokémon Shield**.

This repository is part of the **Generation VIII decompilation cohort** together with Sword, Brilliant Diamond, Shining Pearl, and Pokémon Legends: Arceus. Each game remains an independent reconstruction target.

## 🎯 Goals

- Reconstruct game code and data into readable, editable source form.
- Document executable structures, data formats, scripts, assets, and version differences.
- Preserve Shield-specific behavior instead of assuming identity with Sword.
- Track base game, updates, The Isle of Armor, and The Crown Tundra separately where they differ.
- Keep analysis, tooling, metadata, and documentation reproducible.

## 🚧 Status

Active work has begun with **Phase 0: target intake and reproducibility**. Exact local targets are identified before executable/data mapping and source reconstruction.

See [Decompilation Start](docs/DECOMPILATION_START.md) and [Project Status](docs/PROJECT_STATUS.md).

## 📌 Repository policy

Retail game images, decrypted package archives, console keys, and complete redistributed game binaries are not committed. Reconstructed source, project data, tooling, analysis, manifests, documentation, patches, and reviewable non-ROM work products may be tracked.

## 🧭 Roadmap

- [x] Establish clean repository baseline
- [x] Begin target intake workflow
- [ ] Verify exact Shield base/update/DLC targets
- [ ] Map executable and filesystem structures
- [ ] Begin bounded source reconstruction
- [ ] Document scripts, data formats, assets, and version differences
- [ ] Add reproducible verification and matching workflows

## 📚 Documentation

- [Decompilation start](docs/DECOMPILATION_START.md)
- [Project status](docs/PROJECT_STATUS.md)
- [Roadmap](docs/ROADMAP.md)
- [Version coverage](docs/VERSIONS.md)
- [Research guide](docs/RESEARCH_GUIDE.md)
- [Verification guide](docs/VERIFICATION.md)
- [Repository structure](docs/REPOSITORY_STRUCTURE.md)

## 🔬 Research and verification

Claims must remain tied to an exact target version/revision. Sword/Shield similarities are useful leads, but deduplication or shared-source conclusions require direct evidence such as identical bytes, hashes, structures, or independently reproduced behavior.

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
