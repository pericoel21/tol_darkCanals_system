---
tags:
  - combat
  - core
  - mechanic
aliases:
  - Ranged Combat
  - Shoot
  - Shooting
connections:
description: Combat from a distance
---
# `= this.file.aliases[0]`
> `= this.description`.

## Requisites
- [[traits_ranged|Ranged]] or [[traits_thrown|Thrown]] [[item_weapon|Weapon]].
- Too long of a [[combat_distance|Distance]] might make [[mechanic_difficulty|Difficulty]] `IMPOSSIBLE`.

## Rolling the Attack
- Attacker [[mechanic_rollResolution|Rolls]] [[skill_ballistics|BALLISTICS]] and declares [[combat_hitLocations|Hit Location]].
- No [[mechanic_opposedRolls|Opposed Roll]] or [[combat_reactionsAndCounteractions|Reaction]].
- GM rolls for the [[combat_hitLocations|Hit Location]].

### NPCs Shooting
- PCs can [[reactions_block|BLOCK]] Ranged Attacks:
	- If [[combat_distance|Engaged]] in a [[combat_melee|Melee]], they must spend a [[stat_stamina|Stamina]].
- PCs can [[reactions_dodge|DODGE]] Ranged Attacks only if fired from [[combat_distance|Engaged Range]] (always `VERY EASY` [[mechanic_difficulty|Difficulty]]).
- In any other case, GM rolls for the NPC.

#### Multiple Shooters
- If multiple NPCs shoot a single PC, roll a single attack.
- [[mechanic_difficulty|Difficulty]] is one step `EASIER` per attacker.

### Difficulties when Attacking
#### Moving vs. Aiming
- [[movement|Moving]] on the same makes [[mechanic_difficulty|Difficulty]] `HARDER`.
- If not [[movement|moved]], the attack is considered as "aimed" (`AVERAGE`).

#### Range
- Every [[item_weapon|Weapon]] has an optimal [[combat_distance|Distances]] as per its [[traits_range|Range Trait]].
- [[mechanic_difficulty|Difficulty]] is `HARDER` for every [[combat_distance|Range Band]] (both closer or further).
- When too close, it is never `IMPOSSIBLE` (`VERY HARD` is tme maximum [[mechanic_difficulty|Difficulty]]).
- WHen too far away, [[mechanic_difficulty|Difficulty]] might be `IMPOSSIBLE`.

> In tight spaces, like inside a cramped building, Short range weapons have the advantage over Long range - it takes a little longer to bring a Long bow to bear in cramped space than a Short bow, so more stopping power is not always better!

#### Target Size
- For each [[sizeCategory|Size Category]] `LARGER` than the attacker, the [[mechanic_difficulty|Difficulty]] gets `EASIER`.
- For each [[sizeCategory|Size Category]] `SMALLER` than the attacker, the [[mechanic_difficulty|Difficulty]] gets `HARDER`.

#### Shooting Unseen Targets
- A character might know an enemy is there, but might not see it.
- [[mechanic_difficulty|Difficulty]] is one step `HARDER`.

### Result of the Attack Roll

| [[mechanic_degreesOfSuccess\|Degrees of Success]] | Result                                                                                                                                      |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Negative                                         | Enemy's [[combat_reactionsAndCounteractions\|Counteraction]] succeeds. No [[combat_reactionsAndCounteractions\|Reactions]]. |
| Exactly -1                                       | Above, plus unexpected [[glancingHit\|Glancing Hit]] if shooting into a [[combat_melee\|Melee]]                                     |
| Zero                                             | Glancing Hit                                                                                                                                |
| One                                              | Full hit                                                                                                                                    |
| Two or more                                      | Heavy hit                                                                                                                                   |

- *Glancing Hit:* The attack inflicts one [[mechanic_injury|Injury Level]] lower than normal.
- *Heavy Hit:* The attack inflicts one [[mechanic_injury|Injury Level]] higher than normal.

#### Shooting into a Melee
If shooting a character who is [[combat_distance|Engaged]] with another in a [[combat_melee|Melee]], and the shoot has exactly -1 [[mechanic_degreesOfSuccess|Degrees of Success]], it causes a [[glancingHit|Glancing Hit]] to a random [[combat_hitLocations|Hit Location]] of the other character.
