---
tags:
  - combat
  - core
  - mechanic
  - counteraction
aliases:
  - RIPOSTE (Counteraction)
  - RIPOSTE
connections:
  - "[[skill_fight|FIGHT]]"
description: Counteraction to attempt to deal damage back at an enemy
---
# `= this.file.aliases[0]`
Associated [[mechanic_skills|Skill]]: `= this.connections[0]`
> `= this.description`.

A Riposte works exactly like a [[combat_melee|Melee Attack]].

Using the **same [[weapon|Weapon]]** to [[reactions_block|Block]] or [[reactions_parry|Parry]] and to Riposte **makes the Riposte `HARDER`.**

Used by [[mechanic_rollResolution|rolling]] [[skill_fight|FIGHT]], usually [[mechanic_opposedRolls|Opposed]] by the enemy's [[skill_fight|FIGHT]]:

| [[mechanic_degreesOfSuccess\|Deg. Success]] | Outcome                                                                        |
| ------------------------------------------ | ------------------------------------------------------------------------------ |
| 2+                                         | Defender deals a [[combat_melee#Result of the Attack Roll\|Heavy hit]] |
| 1                                          | Defender deals a [[combat_melee#Result of the Attack Roll\|Full hit]]  |
| 0                                          | [[combat_melee#Result of the Attack Roll\|Glancing hit]] for both      |
| -1                                         | Attacker deals a [[combat_melee#Result of the Attack Roll\|Full hit]]  |
| -2                                         | Attacker deals a [[combat_melee#Result of the Attack Roll\|Heavy hit]] |