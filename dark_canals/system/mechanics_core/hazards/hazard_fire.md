---
tags:
  - core
  - mechanic
  - hazard
aliases:
  - Fire
  - Burn
  - Burning
  - Burning Damage
connections:
description: Fire is handled by a combination of injuries and the exposure condition
---
# `= this.file.aliases[0]`
> `= this.description`.

- Fire damage is handled through the table for [[mechanic_hazards|Hazards]].
- No tracking of timers or turns needed.
- [[mechanic_injury|Injuries]] of `SEVERE` level or higher also cause levels of [[condition_exposure|Exposure Condition]] equal to the fire's rating.
- A single level of [[condition_exposure|Exposure]] per wound caused by fire can be remved by getting the wound into cold water.
- Any number of levels of [[condition_exposure|Exposure]] from fire can be removed with a [[skill_surgery|SURGERY]] roll (by dressing the wounds).

| Severity   | Source                            | [[condition_exposure\|Exposure]] |
| ---------- | --------------------------------- | -------------------------------- |
| `MINOR`    | [[item_candle\|Candle]]           | -                                |
| `SERIOUS`  | [[item_torch\|Torch]]             | -                                |
| `SEVERE`   | [[mechanic_makingCamp\|Campfire]] | 3                                |
| `CRITICAL` | Furnace                           | 4                                |
| `BRUTAL`   | Dragon's Fire                     | 5                                |

