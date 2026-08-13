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
- The attacker and their target are at [[coreMec_combat_distance|Close Range]].
- A melee [[weapon|weapon]] or unarmed attack is used.
- There is no barrier between the attacker and its objective ([[cover|Cover]] has no effect against a Close Attack).

## Rolling the Attack
- The attacker PC rolls [[skill_fight|FIGHT]] and selects a [[hitLocation|Hit Location]].
- The roll is against the enemy's [[skill_mobility|MOBILITY]], [[skill_physique|PHYSIQUE]] or [[skill_fight|FIGHT]], depending on their [[coreMec_combat_reactionsAndCounteractions|Reaction or Counteraction]].
- The GM rolls for the [[hitLocation|Hit Location]].

### Difficulties when Attacking
#### Prone
- A [[prone|Prone]] attacker rolls `HARDER` against standing targets.
- A standing attacker rolls `EASIER` against a [[prone|Prone]] target.
- While [[prone|Prone]], a Character cannot perform [[coreMec_combat_reactionsAndCounteractions|Counteractions]].

#### Defenceless Targets
A defenceless target cannot perform [[coreMec_combat_reactionsAndCounteractions|Reactions or Counteractions]]. When they are attacked, they automatically suffer a Heavy Hit.

##### Unconscious Targets
[[coreMec_fallUnconscious|Unconscious]] targets are always Defenceless.

Attacking an [[coreMec_fallUnconscious|Unconscious]] target requires a [[skill_insight|INSIGHT]] [[coreMec_rollResolution|Roll]].
- *Success:* The attacker's ethics forbid them from attacking.
- *Failure:* The attacker justifies the dishonourable acts and might attack (the [[stat_stress|Stress]] from the failed [[coreMec_rollResolution|Roll]] comes from that).

### Result of the Attack Roll

| [[coreMec_degreesOfSuccess\|Degrees of Success]] | Result                                                                                         |
| ------------------------------------------------ | ---------------------------------------------------------------------------------------------- |
| Negative                                         | The enemy's [[coreMec_combat_reactionsAndCounteractions\|Reaction or Counteraction]] succeeds. |
| Zero                                             | Glancing Hit                                                                                   |
| One                                              | Full hit                                                                                       |
| Two or more                                      | Heavy hit                                                                                      |

- *Glancing Hit:* The attack inflicts one [[coreMec_injury|Injury Level]] lower than normal.
- *Heavy Hit:* The attack inflicts one [[coreMec_injury|Injury Level]] higher than normal.