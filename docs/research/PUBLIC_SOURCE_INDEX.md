# Public Source Index

This is the living source index for the ROM-less reconstruction of **Pocket Monsters Shield / Pokémon Shield**.

The project has no locally owned retail dump. Publicly accessible evidence is therefore surveyed exhaustively, with the **Japanese release used as the comparison baseline** and all regional, language, revision, update, distribution, DLC, storefront, and online-service differences preserved rather than normalized away.

## Evidence policy

- Japanese official material is the baseline for release chronology, Japanese terminology, Japan-specific distributions, and Japanese publication dates.
- Shield is tracked independently from Sword even when an official or technical source covers both versions.
- A regional storefront or language surface is not evidence of a distinct program/content binary unless independently established.
- Public reverse-engineering projects remain `Unverified / external evidence` for target claims until independently corroborated.
- Unknown hashes, cartridge revisions, content identities, Title IDs, and regional binary relationships remain `TBD` rather than guessed.
- Isle of Armor and Crown Tundra are major Shield-linked workstreams and are not treated as small appendices.

## Official Japanese baseline sources

| ID | Source | Coverage |
| --- | --- | --- |
| `OFF-JP-SWSH-LINEUP` | https://www.pokemon.co.jp/ex/sword_shield/lineup/190605_01.html | Japanese launch metadata; 2019-11-15 release; package/download; nine supported languages |
| `OFF-JP-SWSH-NEWS` | https://www.pokemon.co.jp/ex/sword_shield/news/ | Dedicated Sword/Shield news discovery index |
| `OFF-JP-SWSH-EXPANSION` | https://www.pokemon.co.jp/ex/sword_shield_expansion/ | Expansion Pass, Isle of Armor and Crown Tundra primary site |
| `OFF-JP-UPD-110` | https://www.pokemon.co.jp/info/2020/01/200109_at01.html | Ver.1.1.0 |
| `OFF-JP-UPD-111` | https://www.pokemon.co.jp/info/2020/03/200318_at01.html | Ver.1.1.1 |
| `OFF-JP-UPD-120` | https://www.pokemon.co.jp/info/2020/06/200617_at01.html | Ver.1.2.0 / Isle of Armor support |
| `OFF-JP-UPD-121` | https://www.pokemon.co.jp/info/2020/07/200708_at01.html | Ver.1.2.1 |
| `OFF-JP-UPD-130` | https://www.pokemon.co.jp/info/2020/10/201023_at01.html | Ver.1.3.0 / Crown Tundra support |
| `OFF-JP-UPD-131` | https://www.pokemon.co.jp/info/2020/12/201222_at01.html | Ver.1.3.1 |
| `OFF-JP-UPD-132` | https://www.pokemon.co.jp/info/2021/05/210512_at01.html | Ver.1.3.2 |

## Primary Shield-specific comparison axes

- Shield-exclusive Pokémon and encounters;
- Shield-exclusive Gym leaders and story-facing version differences;
- Shield-side Max Raid and Wild Area event data;
- version-dependent gifts and Dynamax Crystal redemption;
- version-specific legendary and DLC encounter choices where applicable;
- packaging / SKU / rating / retailer differences;
- local and online compatibility by update version;
- language and regional presentation differences against the Japanese baseline.

## Public reverse-engineering and technical sources

| ID | Source | Relevant evidence |
| --- | --- | --- |
| `RE-PKNX` | https://github.com/kwsch/pkNX | Sword/Shield file mappings, FlatBuffers schemas, message paths, encounters, raids, trainers, PML data, placement and editors |
| `RE-PKHEX` | https://github.com/kwsch/PKHeX | SAV8SWSH, PK8, save blocks, legality, encounter/event and HOME-related research |
| `RE-CAPTURESIGHT` | https://github.com/zaksabeast/CaptureSight | runtime RAM structures, encounter/raid/trade and RNG observations |
| `RE-RAIDFINDER` | https://github.com/Admiral-Fish/RaidFinder | historical Max Raid RNG research; upstream repository is archived |
| `RE-RAID-PLUGIN` | https://github.com/Leanny/PKHeX_Raid_Plugin | raid save/event/RNG research |
| `RE-RNG-GUIDES` | https://github.com/zaksabeast/PokemonRNGGuides | public RNG research corpus |
| `RE-SWSH-RNG-TOOL` | https://github.com/lincoln-lm/swsh-rng-tool | Sword/Shield RNG tooling/research |
| `RE-SYSBOT` | https://github.com/kwsch/SysBot.NET | runtime automation and seed-check research |
| `RE-SWSH-MODS-EXL` | https://github.com/lincoln-lm/swsh-mods-exl | ExeFS/runtime hooks for modern Sword/Shield builds |
| `RE-SWITCH-TOOLBOX` | https://github.com/KillzXGaming/Switch-Toolbox | Game Freak model/archive/texture workflows |
| `RE-MODEL-IMPORTER` | https://github.com/ChicoEevee/Pokemon-Switch-Model-Importer-Blender | model/animation format research |
| `RE-GFBANM` | https://github.com/Shararamosh/io_scene_gfbanm | `.gfbanm` animation format research |
| `RE-HACTOOL` | https://github.com/SciresM/hactool | Switch NCA/ExeFS/RomFS/NSO container context |

## Event / distribution / network archives

| ID | Source | Coverage |
| --- | --- | --- |
| `DB-PP-SWSH` | https://projectpokemon.org/home/files/category/225-sword-shield/ | Sword/Shield Generation VIII event archive; currently 215 category records observed in the broader census |
| `DB-PP-GEN8` | https://projectpokemon.org/home/files/category/2-event-gallery/ | Generation VIII event discovery root |

The Shield repository will independently classify the shared 215-record Sword/Shield archive by applicability (`Shield`, `Sword`, `both`, version-dependent, regional, superseded, unreleased/beta) rather than copying Sword conclusions blindly.

## Source families that require exhaustive enumeration

- all Japanese dedicated Sword/Shield pages plus off-index `pokemon.co.jp/info/` material;
- all Shield-relevant Expansion Pass pages;
- all Japanese distributions, serial codes, local wireless gifts, items, clothing and Dynamax Crystals;
- all Wild Area News / Max Raid event revisions and server-side replacements;
- all Battle Stadium seasons, ranked rules, Internet/Friendly/Live competitions and rewards;
- all HOME notices and transfer/remap behavior relevant to Shield;
- every official regional/language site and removed/archived counterpart;
- Project Pokémon event/Wild Area records;
- pkNX / PKHeX / runtime / RNG / asset-format repositories and materially different forks;
- Bulbapedia, Serebii, Showdown/Smogon, TCRF and attributable datamine/community research as secondary discovery/cross-check sources;
- packaging, cartridge revisions, ratings, JAN/UPC/EAN/SKU and public content-identity evidence;
- pre-release videos/screenshots, unused/replaced data, bugs and patch-fixed behavior.

## Completion rule

A representative sample is never enough. Each source family progresses through `Not started → Enumerating → Indexed → Reviewed → Cross-checked → Exhausted`. `Exhausted` means repeated searches across alternate names, languages, domains, archives and referenced projects produced no additional material at the survey date; it is not a claim that the Internet can be proven complete forever.

_Last surveyed: 2026-09-14._
