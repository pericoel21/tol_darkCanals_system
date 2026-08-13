---
tags:
  - combat
  - core
  - mechanic
  - reaction
aliases:
  - PARRY (Reaction)
  - PARRY
connections:
  - "[[skill_fight|FIGHT]]"
description: Reaction to attempt to deflect the incoming damage with a weapon
---
# `= this.file.aliases[0]`
Associated [[coreMec_skills|Skill]]: `= this.connections[0]`
> `= this.description`.

Used by [[coreMec_rollResolution|rolling]] [[skill_fight|FIGHT]], usually [[coreMec_opposedRolls|Opposed]] by the enemy's [[skill_fight|FIGHT]]:

| [[coreMec_degreesOfSuccess\|Deg. Success]] | Outcome                                                          |
| ------------------------------------------ | ---------------------------------------------------------------- |
| 1+                                         | Avoid hit                                                        |
| 0                                          | [[coreMec_combat_melee#Result of the Attack Roll\|Glancing hit]] |
| -1                                         | [[coreMec_combat_melee#Result of the Attack Roll\|Full hit]]     |
| -2                                         | [[coreMec_combat_melee#Result of the Attack Roll\|Heavy hit]]    |

## Parrying is Tricky
To get the [[coreMec_modifier|Modifier]] to Parry, the PC must both:
- Use a [[weapon|Weapon]] with the [[trait_parrying|Parrying Trait]].
- Have the [[profficiency_parrying|Parrying]] [[coreMec_profficiencies|Proficiency]].
