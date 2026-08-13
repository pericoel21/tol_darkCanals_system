---
tags:
  - combat
  - core
  - mechanic
  - reaction
aliases:
  - DODGE (Reaction)
  - DODGE
connections:
  - "[[skill_mobility|MOBILITY]]"
description: Reaction to attempt to move out of the way of an attack
---
# `= this.file.aliases[0]`
Associated [[coreMec_skills|Skill]]: `= this.connections[0]`
> `= this.description`.

Used by [[coreMec_rollResolution|rolling]] [[skill_mobility|MOBILITY]], usually [[coreMec_opposedRolls|Opposed]] by the enemy's [[skill_fight|FIGHT]]:

| [[coreMec_degreesOfSuccess\|Deg. Success]] | Outcome                                                          |
| ------------------------------------------ | ---------------------------------------------------------------- |
| 1+                                         | Avoid hit                                                        |
| 0                                          | [[coreMec_combat_melee#Result of the Attack Roll\|Glancing hit]] |
| -1                                         | [[coreMec_combat_melee#Result of the Attack Roll\|Full hit]]     |
| -2                                         | [[coreMec_combat_melee#Result of the Attack Roll\|Heavy hit]]    |