---
tags:
  - combat
  - core
  - mechanic
aliases:
  - Armour
connections:
description: Armour protects a specific part of the body, and it can be layered
---
# `= this.file.aliases[0]`
> `= this.description`.

Armour has a level, from 1 to 4, which corresponds with a [[coreMec_injury|Level of Injury]]
.
## Using Armour
When a PC receives an [[coreMec_injury|Injury]] on a [[hitLocation|Hit Location]] which is protected by armour, compare the armour level to the [[coreMec_injury|Injury Level]]:
- If the Armour Level is greater, the [[coreMec_injury|Injury]] is disregarded.
- Else, the Armour Level is subtracted from the [[coreMec_injury|Injury Level]]. The resulting number is the [[coreMec_injury|Level of the Injury]] that the PC receives.

### Armour damage
> See [[repairingArmour|Repairing Armour]]
- [[weapon|Weapons]] might have traits which damage a specific type of [[armour|Armour]].
- Damage to [[armour|Armour]] only happens on an attack which generates an [[coreMec_injury|Injury]] (so, when it equals or exceeds the Armor Level).
- Only the outermost, un-damaged armour can be damaged.
- Once the armour is damaged, it no longer provides benefits.

### Stealth in Armour
> See [[stealth|Stealth]]

Any mail or plate armour makes [[skill_mobility|MOBILITY]] checks `HARDER` when the objective is to do stuff quietly.

## Tracking Armour
- Outline the corresponding box for the level of the armour, when equipping that armour.
- Cross the box for that armour's level once the armor becomes damaged.