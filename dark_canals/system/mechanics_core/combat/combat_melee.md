---
tags:
  - combat
  - core
  - mechanic
aliases:
  - Close Combat
  - Melee
  - Melee Combat
connections:
description: Melee combat is a dance of actios, counteractions and stamina management
---
# `= this.file.aliases[0]`
> `= this.description`.

## Requisites
- The attacker and their target are at [[combat_distance|Close Range]].
- A melee [[weapon|weapon]] or unarmed attack is used.
- There is no barrier between the attacker and its objective ([[cover|Cover]] has no effect against a Close Attack).

## Rolling the Attack
- Attacker uses [[skill_fight|FIGHT]] and declares [[combat_hitLocations|Hit Location]].
- [[mechanic_opposedRolls|Opposed Roll]] against target's [[skill_mobility|MOBILITY]], [[skill_physique|PHYSIQUE]] or [[skill_fight|FIGHT]], depending on [[combat_reactionsAndCounteractions|Reaction or Counteraction]].
- GM rolls for the [[combat_hitLocations|Hit Location]].

### Difficulties when Attacking
#### Target Size
- For each [[sizeCategory|Size Category]] `LARGER` than the attacker, the [[mechanic_difficulty|Difficulty]] gets `EASIER`.
- For each [[sizeCategory|Size Category]] `SMALLER` than the attacker, the [[mechanic_difficulty|Difficulty]] gets `HARDER`.

#### Prone
- A [[prone|Prone]] attacker rolls `HARDER` against standing targets.
- A standing attacker rolls `EASIER` against a [[prone|Prone]] target.
- While [[prone|Prone]], a Character cannot perform [[combat_reactionsAndCounteractions|Counteractions]].

#### Defenceless Targets
A defenceless target cannot perform [[combat_reactionsAndCounteractions|Reactions or Counteractions]]. When they are attacked, they automatically suffer a Heavy Hit.

##### Unconscious Targets
[[mechanic_fallUnconscious|Unconscious]] targets are always Defenceless.

Attacking an [[mechanic_fallUnconscious|Unconscious]] target requires a [[skill_insight|INSIGHT]] [[mechanic_rollResolution|Roll]].
- *Success:* The attacker's ethics forbid them from attacking.
- *Failure:* The attacker justifies the dishonourable acts and might attack (the [[stat_stress|Stress]] from the failed [[mechanic_rollResolution|Roll]] comes from that).

### Result of the Attack Roll

| [[mechanic_degreesOfSuccess\|Degrees of Success]] | Result                                                                                     |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| Negative                                         | Enemy's [[combat_reactionsAndCounteractions\|Reaction or Counteraction]] succeeds. |
| Zero                                             | Glancing Hit                                                                               |
| One                                              | Full hit                                                                                   |
| Two or more                                      | Heavy hit                                                                                  |

- *Glancing Hit:* The attack inflicts one [[mechanic_injury|Injury Level]] lower than normal.
- *Heavy Hit:* The attack inflicts one [[mechanic_injury|Injury Level]] higher than normal.