---
tags:
  - core
  - mechanic
aliases:
  - Stealth
  - Sneaking
connections:
description: Stealthing doesn't avoid being seen; it avoids being noticed
---
# `= this.file.aliases[0]`
> `= this.description`.

## Spotting Someone
- When a character looks at something, they see perfectly what's there.
- **Lookout** character **rolls [[skill_observation|OBSERVATION]].**
- Lookouts **automatically notice** non-hiden, non-stealthing characters.
- If **lookout is sufficiently distracted: Automatic success** on hiding or stealthing.
- Multiple lookouts: Use highest [[skill_observation|OBSERVATION]].

#### External Factors
- Factor affects **perception:** Change **lookout's [[mechanic_difficulty|Difficulty]].**
- Factor affects **movement:** Change **sneaking [[mechanic_difficulty|Difficulty]].**


| [[combat_distance\|Distance]] | [[skill_mobility\|MOBILITY]] | [[skill_observation\|OBSERVATION]] |
| ------------------------------------- | ---------------------------- | ---------------------------------- |
| [[distance_far\|FAR]]                 | `VERY EASY`                  | `VERY HARD`                        |
| [[distance_long\|LONG]]               | `EASY`                       | `HARD`                             |
| [[distance_short\|SHORT]]             | `HARD`                       | `EASY`                             |
| [[distance_close\|CLOSE]]             | `VERY HARD`                  | `VERY EASY`                        |

### Sneaking
- [[mechanic_opposedRolls|Opposed Roll]] of [[skill_mobility|MOBILITY]] vs. [[skill_observation|OBSERVATION]].
- [[mechanic_degreesOfSuccess|Partial Success]]: Lookout notices something, but is unsure what exactly.



### Hiding
- Hidden character **doesn't roll.**
- Lookout roll's **[[mechanic_difficulty|Difficulty]]:** Determined by the **quality of the hiding spot.**

### Sneak Attack & Ambush
| [[mechanic_degreesOfSuccess\|Deg. Success]] | Outcome                                                                                                                       |
| ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| -1 or less                                 | Target sees attacker coming, [[combat_reactionsAndCounteractions\|React & Counteract]] as normal.                     |
| 0                                          | Attack succeeds, target cannot [[combat_reactionsAndCounteractions\|Counteract]].                                     |
| 1 or more                                  | Attack succeeds, target cannot [[combat_reactionsAndCounteractions\|Counteract]] and is [[defenceless\|Defenceless]]. |
#### Sneak Attack
- Attack while Sneaking.
- [[mechanic_opposedRolls|Opposed Roll]]: [[skill_mobility|MOBILITY]] vs. [[skill_observation|OBSERVATION]].
- Single roll used both for approach and attack.

#### Ambush
- Atack from hiding spot.
- Target must be at least within [[combat_distance|Close Range]].

##### Exiting Hiding Spot
- Move as normal.
- Then, if within [[combat_distance|Short Range]]: Attack with [[skill_mobility|MOBILITY]], [[mechanic_difficulty|Difficulty]] set by hiding spot (not target's [[skill_observation|OBSERVATION]]).
