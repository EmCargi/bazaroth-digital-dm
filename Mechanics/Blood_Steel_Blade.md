# The Two-Doctrine Blood-Steel Blade

> **Source:** CP-2 (gear Item rail) + Bazaroth Cauldron blood-metal.

## The Signature Asset

The demo's signature gear is a **blood-steel blade** — forged from the Cauldron's blood-metal, 20 CP, `gear` item, Size Rank 0. Two doctrines, one chassis (mirrors psycho-frame/skiff/staff/harp):

| Doctrine | Item | Effect | Flavor |
|---|---|---|---|
| **King's Legion Blade** | `bazaroth_legion_blade` | `{"kind":"stat_mod","acv_bonus":2,"ar":0,"note":"Forged from the Cauldron's blood-metal, bound to the Infernal King"}` | The legal lane — the legion's blade |
| **Bloom-Changed Blade** | `bazaroth_bloom_blade` | Same bonus + `Defect: Tainted (Marked)` returning 2 CP → `Weapon Enhancement: Drain` | The forsaken lane — mutated in the Bloom |

Both: 20 CP, rank C, `item_type: gear`, granted as starting gear (not a market buyout).

## Attributes

- Legion blade: blood-steel weapon (ACV +2 via `stat_mod`)
- Bloom blade: mutated, drains on a hit (Drain enhancement)

## Engine Path

One `gear` row per doctrine in the `items` table, `effect_json` structured for `models.py`. No new engine field — exactly the CP-2 rail from Enid (chassis) / Cathedral (skiff) / Ikaris (staff) / Aradia (harp).