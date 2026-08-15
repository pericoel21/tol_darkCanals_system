---
tags:
aliases:
  - Reactions & Counteractions
  - Reaction
  - Reactions
  - Counteraction
  - Counteractions
connections:
description: Every time a character attacks another, the defender has an opportunity to react, and to do something about it
---
# `= this.file.aliases[0]`
> `= this.description`.

## Definitions
- *Reaction:* An action to avoid getting hurt.
- *Counteraction:* An action to take advantage if the attacker misses.

## Reacting & Counteracting
If a character is targeted by a  [[combat_melee|Melee Attack]], they chose one Reaction, one Counteraction, or any combination of one of each.

In any case, reactions and counteractions are resolved with a single [[mechanic_rollResolution|Roll]], usually against [[skill_fight|FIGHT]].

Every Reaction and Counteraction has an associated [[mechanic_skills|Skill]]. When choosing to perform both a Reaction and a Counteraction, the character uses the lowest of the associated [[mechanic_skills|Skills]].

## Reactions
Not performing a Reaction causes the defender to automatically suffer a [[combat_melee#Result of the Attack Roll|Heavy hit]].

| [[mechanic_degreesOfSuccess\|Degrees of Success]] | [[reactions_dodge\|DODGE]] ([[skill_mobility\|MOBILITY]])        | [[reactions_parry\|PARRY]] ([[skill_fight\|FIGHT]])              | [[reactions_block\|BLOCK]] ([[skill_physique\|PHYSIQUE]])                      |
| ------------------------------------------------ | ---------------------------------------------------------------- | ---------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| 2+                                               | Avoid hit                                                        | Avoid hit                                                        | [[combat_melee#Result of the Attack Roll\|Full hit]] (Arm / Item held) |
| 1                                                | Avoid hit                                                        | Avoid hit                                                        | [[combat_melee#Result of the Attack Roll\|Full hit]] (Arm / item held) |
| 0                                                | [[combat_melee#Result of the Attack Roll\|Glancing hit]] | [[combat_melee#Result of the Attack Roll\|Glancing hit]] | [[combat_melee#Result of the Attack Roll\|Heavy hit]] (Arm/item held)  |
| -1                                               | [[combat_melee#Result of the Attack Roll\|Full hit]]     | [[combat_melee#Result of the Attack Roll\|Full hit]]     | [[combat_melee#Result of the Attack Roll\|Full hit]]                   |
| -2                                               | [[combat_melee#Result of the Attack Roll\|Heavy hit]]    | [[combat_melee#Result of the Attack Roll\|Heavy hit]]    | [[combat_melee#Result of the Attack Roll\|Heavy hit]]                  |

## Counteractions

| [[mechanic_degreesOfSuccess\|Degrees of Success]] | [[couteraction_manoeuvre\|MANOEUVRE]] ([[skill_mobility\|MOBILITY]]) | [[couteraction_riposte\|RIPOSTE]] ([[skill_fight\|FIGHT]])                     | [[couteraction_shove\|SHOVE]] ([[skill_physique\|PHYSIQUE]])     |
| ------------------------------------------------ | -------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ---------------------------------------------------------------- |
| 2+                                               | Move Closer / Further                                                | Defender deals a [[combat_melee#Result of the Attack Roll\|Heavy hit]] | Shove opponent                                                   |
| 1                                                | Move Closer / Further                                                | Defender deals a [[combat_melee#Result of the Attack Roll\|Full hit]]  | Shove opponent                                                   |
| 0                                                | [[combat_melee#Result of the Attack Roll\|Glancing hit]]     | [[combat_melee#Result of the Attack Roll\|Glancing hit]] for both      | [[combat_melee#Result of the Attack Roll\|Glancing hit]] |
| -1                                               | [[combat_melee#Result of the Attack Roll\|Full hit]]         | Attacker deals a [[combat_melee#Result of the Attack Roll\|Full hit]]  | [[combat_melee#Result of the Attack Roll\|Full hit]]     |
| -2                                               | [[combat_melee#Result of the Attack Roll\|Heavy hit]]        | Attacker deals a [[combat_melee#Result of the Attack Roll\|Heavy hit]] | [[combat_melee#Result of the Attack Roll\|Heavy hit]]    |
