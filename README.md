# 💿 Bazaroth: The Demon Sun — Game Disc for Chronos Core

*The dying world of the Demon Sun. Hellspawn, the Infernal King's Citadel of Fire, the Bloom, the Plain of Despair, and the Pilgrimage of Bloods.*

> **Source:** BESM 4e Chapter 14 (Anime Multiverse) — First-party canon, no third-party IP.
> All content authored from the canon hooks. Regenerable via the Chronos engine.

---

## 🎮 Boot (when ready)

```text
/setting besm_bazaroth       # swap discs in the TUI
/roster                      # Brand column
/module pilgrimage_of_bloods.json             # default starter module
```

| Contract layer | Status |
|---|---|
| **1 · Registration** | ✅ `besm_bazaroth` in `config/settings.json` → `pilgrimage_of_bloods.json` |
| **2 · Module** | ✅ `modules/pilgrimage_of_bloods.json` (validator-passed) |
| **3 · Roster** | ✅ Starter characters authored (`Characters/`, 50 CP, `besm_bazaroth`) |
| **4 · Economy** | ✅ Seed catalog + chassis as `Item` |
| **5 · Lore Vault** | 🏗️ `World/` `Characters/` `Factions/` `Locations/` `Mechanics/` |

> **Status: SCAFFOLDED** — disc directory + proposal exist. Layers 1–5 wired via Chronos Core engine.

## 🗂️ Structure

```
bazaroth-digital-dm/
├── README.md               ← this home page
├── Characters/             ← PC/NPC sheets (besm_bazaroth)
├── data/                   ← roster DB + catalog
├── Factions/               ← organizations & groups
├── Locations/              ← region & landmark sheets
├── Mechanics/              ← system rules & supplements
├── modules/                ← playable labyrinth modules
├── scripts/                ← import/parser utilities
└── World/                  ← lore vault
```

---

*Disc for the Chronos Core console. Swap via `/setting besm_bazaroth`.*
