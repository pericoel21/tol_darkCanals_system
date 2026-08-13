---
tags:
  - combat
  - core
  - mechanic
  - reaction
aliases:
  - BLOCK (Reaction)
  - BLOCK
connections:
  - "[[skill_physique|PHYSIQUE]]"
description: Reaction to attempt to block the incoming damage with an item or the bare hands
---
# `= this.file.aliases[0]`
Associated [[coreMec_skills|Skill]]: `= this.connections[0]`
> `= this.description`.

When Blocking, the character **selects which item or arm is going to get hit.**

Used by [[coreMec_rollResolution|rolling]] [[skill_physique|PHYSIQUE]], usually [[coreMec_opposedRolls|Opposed]] by the enemy's [[skill_fight|FIGHT]]:

| [[coreMec_degreesOfSuccess\|Deg. Success]] | Outcome                                                                        |
| ------------------------------------------ | ------------------------------------------------------------------------------ |
| 1+                                         | [[coreMec_combat_melee#Result of the Attack Roll\|Full hit]] (Arm / item held) |
| 0                                          | [[coreMec_combat_melee#Result of the Attack Roll\|Heavy hit]] (Arm/item held)  |
| -1                                         | [[coreMec_combat_melee#Result of the Attack Roll\|Full hit]]                   |
| -2                                         | [[coreMec_combat_melee#Result of the Attack Roll\|Heavy hit]]                  |

## Blocking with Items
If the Block is performed using an **item,** and it succeeds:
- If the **[[item|Item]] rating** is **lower** than the **[[coreMec_injury|Injury rating]],** the item **gets [[damagedItem|Damaged]].**
- If an item gets **[[damagedItem|Damaged]] a second time,** it is **destroyed.**
- [[traits_rusty|Rusty]] items count as damaged.

### Item Rating
- *[[weapon|Weapons]]:* Equal to their [[coreMec_injury|Injury Rating]].
- *Can be used as [[improvisedWeapon|Improvised Weapon]]:* Possibly **[[coreMec_injury|Serious Injury (1)]] rating.**
- *Smaller than a [[weapons_dagger|Dagger]]:* Cannot Block.

### Using Shields
[[item_shield|Shields]] are destroyed if both:
- Attacking [[weapon|Weapon]] has the [[traits_hacking|Hacking Trait]].
- [[coreMec_injury|Injury Rating]] is equal or higher than the [[item_shield|Shield's]] [[coreMec_armour|Armour Rating]].
