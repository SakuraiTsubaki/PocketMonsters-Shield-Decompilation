# Version Coverage

Use this document as the authoritative inventory of game versions targeted by this decompilation project.

The repository currently has **no locally owned retail dump**. Rows below are therefore `Reference only` unless stronger target identity evidence is available. Japanese official material is the chronology baseline; regional publication dates and binary identities are tracked separately.

| Status | Region | Language | Revision / update | Official JP date | Hashes | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Reference only | JP baseline | 9 languages officially supported | Launch release | 2019-11-15 | TBD | Product page confirms package/download release and nine languages. Internal launch version/build identity remains TBD. |
| Reference only | JP baseline | multilingual identity TBD | 1.1.0 | 2020-01-10 | TBD | Expansion Pass purchase entry point, Wedgehurst Station event and fixes. |
| Reference only | JP baseline | multilingual identity TBD | 1.1.1 | 2020-03-18 | TBD | Tampered-Pokémon-data handling and additional fixes. |
| Reference only | JP baseline | multilingual identity TBD | 1.2.0 | 2020-06-17 | TBD | Isle of Armor support and additional Pokémon/data. |
| Reference only | JP baseline | multilingual identity TBD | 1.2.1 | 2020-07-08 | TBD | Link-code/password matching fix and additional fixes. |
| Reference only | JP baseline | multilingual identity TBD | 1.3.0 | 2020-10-23 | TBD | Crown Tundra support and additional Pokémon/data. |
| Reference only | JP baseline | multilingual identity TBD | 1.3.1 | 2020-12-22 | TBD | Bug fixes. |
| Reference only | JP baseline | multilingual identity TBD | 1.3.2 | 2021-05-12 | TBD | Communication-battle icon fix and additional fixes. |

## Japanese primary sources

- Launch/product metadata: https://www.pokemon.co.jp/ex/sword_shield/lineup/190605_01.html
- Ver.1.1.0: https://www.pokemon.co.jp/info/2020/01/200109_at01.html
- Ver.1.1.1: https://www.pokemon.co.jp/info/2020/03/200318_at01.html
- Ver.1.2.0: https://www.pokemon.co.jp/info/2020/06/200617_at01.html
- Ver.1.2.1: https://www.pokemon.co.jp/info/2020/07/200708_at01.html
- Ver.1.3.0: https://www.pokemon.co.jp/info/2020/10/201023_at01.html
- Ver.1.3.1: https://www.pokemon.co.jp/info/2020/12/201222_at01.html
- Ver.1.3.2: https://www.pokemon.co.jp/info/2021/05/210512_at01.html

## Required unresolved inventory

- exact launch build/version field and cryptographic hashes;
- authoritative Shield Title ID/content/update identifiers with provenance;
- physical game-card revisions and cartridges bundling later updates;
- Japan/Korea/NA/EU/HK/TW/AU/NZ/other region content identity relationships;
- whether regional storefront/date differences correspond to any binary/content difference;
- exact DLC/update dependency matrix for base game, Isle of Armor and Crown Tundra;
- local-communication compatibility rules across every update pair;
- historical eShop/product revisions and delisted/changed metadata.

## Status vocabulary

- **Planned** — intended for investigation but not yet verified.
- **Verified** — identity and hashes confirmed.
- **Mapped** — executable/data layout documented.
- **In progress** — active source reconstruction.
- **Matched** — reconstruction verified against the target.
- **Reference only** — public evidence exists but target identity/hashes are not independently verified.

## Recording rules

1. Record exact revision/update information whenever known.
2. Prefer cryptographic hashes over filenames as identity evidence.
3. Do not commit retail game images or console keys.
4. Record regional/language differences instead of assuming two releases are identical.
5. Keep Shield-specific findings separate from Sword even when a shared source covers both games.
6. Link version-specific findings to relevant documentation and source manifests.
