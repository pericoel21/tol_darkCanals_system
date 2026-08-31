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
- [[mechanic_injury|Injuries]] of `SEVERE` level or higher also cause levels of [[condition_exposure|Exposure Condition]] (see table).
- Levels of exposure from fire are tracked by marking boxes with an F.
- Levels of [[condition_exposure|Exposure]] caused by fire can be remved by getting the wound into cold water.
- Any number of levels of [[condition_exposure|Exposure]] from fire can be removed with a [[skill_surgery|SURGERY]] roll (when dressing the wounds).

| Severity   | Source                            | [[condition_exposure\|Exposure]] |
| ---------- | --------------------------------- | -------------------------------- |
| `MINOR`    | [[item_candle\|Candle]]           | -                                |
| `SERIOUS`  | [[item_torch\|Torch]]             | -                                |
| `SEVERE`   | [[mechanic_makingCamp\|Campfire]] | 1                                |
| `CRITICAL` | Furnace                           | 2                                |
| `BRUTAL`   | Dragon's Fire                     | 3                                |

