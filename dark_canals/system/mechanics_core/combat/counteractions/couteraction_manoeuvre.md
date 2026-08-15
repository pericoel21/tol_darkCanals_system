---
tags:
  - combat
  - core
  - mechanic
  - counteraction
aliases:
  - MANOEUVRE (Counteraction)
  - MANOEUVRE
connections:
  - "[[skill_mobility|MOBILITY]]"
description: Counteraction to attempt to reposition
---
# `= this.file.aliases[0]`
Associated [[mechanic_skills|Skill]]: `= this.connections[0]`
> `= this.description`.

Allows the user to **move one [[combat_distance|Range Category]]** from the enemy:
- *Moving Further:* Counts as [[combat_disengage|Disengage]].
- *Moving Closer:* Can initiate a [[combat_grappling|Grapple]].

Used by [[mechanic_rollResolution|rolling]] [[skill_mobility|MOBILITY]], usually [[mechanic_opposedRolls|Opposed]] by [[skill_fight|FIGHT]]:

| [[mechanic_degreesOfSuccess\|Deg. Success]] | Outcome                                                          |
| ------------------------------------------ | ---------------------------------------------------------------- |
| 2+                                         | Manoeuver successfully                                           |
| 1                                          | Manoeuver successfully                                           |
| 0                                          | [[combat_melee#Result of the Attack Roll\|Glancing hit]] |
| -1                                         | [[combat_melee#Result of the Attack Roll\|Full hit]]     |
| -2                                         | [[combat_melee#Result of the Attack Roll\|Heavy hit]]    |
