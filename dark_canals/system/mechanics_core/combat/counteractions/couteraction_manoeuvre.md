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
Associated [[coreMec_skills|Skill]]: `= this.connections[0]`
> `= this.description`.

Allows the user to **move one [[coreMec_combat_distance|Range Category]]** from the enemy:
- *Moving Further:* Counts as [[coreMec_combat_disengage|Disengage]].
- *Moving Closer:* Can initiate a [[coreMec_combat_grappling|Grapple]].

Used by [[coreMec_rollResolution|rolling]] [[skill_mobility|MOBILITY]], usually [[coreMec_opposedRolls|Opposed]] by [[skill_fight|FIGHT]]:

| [[coreMec_degreesOfSuccess\|Deg. Success]] | Outcome                                                          |
| ------------------------------------------ | ---------------------------------------------------------------- |
| 2+                                         | Manoeuver successfully                                           |
| 1                                          | Manoeuver successfully                                           |
| 0                                          | [[coreMec_combat_melee#Result of the Attack Roll\|Glancing hit]] |
| -1                                         | [[coreMec_combat_melee#Result of the Attack Roll\|Full hit]]     |
| -2                                         | [[coreMec_combat_melee#Result of the Attack Roll\|Heavy hit]]    |
