---
tags:
  - core
  - hazard
  - mechanic
aliases:
  - Explosions
  - Explosion
  - Explosive Damage
connections:
  - "[[mechanic_hazards|Hazards]]"
description: Explosion damage depends on the power of the source and the distance to it
---
# `= this.file.aliases[0]`
See `= this.connections[0]`

> `= this.description`.

- Explosions use the generalized table for [[mechanic_hazards|Hazards]].
- At [[combat_distance|Engaged Range]], they deal the full severity of [[mechanic_injury|Injury]].
- Each [[combat_distance|Range Category]] away from the explosion reduces the damage by one category.

| Severity   | Source                                  |
| ---------- | --------------------------------------- |
| `MINOR`    | River rock on a fire                    |
| `SERIOUS`  | [[item_oilFlask\|Oil Flask]]            |
| `SEVERE`   | [[item_lantern\|Lantern]]               |
| `CRITICAL` | [[item_gunpowderKeg\|Keg of Gumpowder]] |
| `BRUTAL`   |                                         |

