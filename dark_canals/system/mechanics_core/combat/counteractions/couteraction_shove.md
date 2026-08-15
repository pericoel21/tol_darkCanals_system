---
tags:
  - combat
  - core
  - mechanic
  - counteraction
aliases:
  - SHOVE (Counteraction)
  - SHOVE
connections:
  - "[[skill_physique|PHYSIQUE]]"
description: Counteraction to attempt to move an enemy
---
# `= this.file.aliases[0]`
Associated [[mechanic_skills|Skill]]: `= this.connections[0]`
> `= this.description`.

**Moves an enemy one [[combat_distance|Range Category]]** further away.

Using a [[item_shield|Shield]] and having [[proficiencies_shield|Shield Profficiency]] gives the [[mechanic_modifier|Modifier]] to the [[mechanic_rollResolution|Roll]].

Used by [[mechanic_rollResolution|rolling]] [[skill_physique|PHYSIQUE]], usually [[mechanic_opposedRolls|Opposed]] by the enemy's [[skill_fight|FIGHT]]:

| [[mechanic_degreesOfSuccess\|Deg. Success]] | Outcome                                                          |
| ------------------------------------------ | ---------------------------------------------------------------- |
| 2+                                         | Shove opponent                                                   |
| 1                                          | Shove opponent                                                   |
| 0                                          | [[combat_melee#Result of the Attack Roll\|Glancing hit]] |
| -1                                         | [[combat_melee#Result of the Attack Roll\|Full hit]]     |
| -2                                         | [[combat_melee#Result of the Attack Roll\|Heavy hit]]    |
