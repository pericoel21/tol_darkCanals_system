---
tags:
  - core
  - mechanic
aliases:
  - Difficulty
connections:
description: Changes to the desired outcome of a roll, representing external factors.
---
# `= this.file.aliases[0]`
> `= this.description`.

Every significant external factor affecting a [[dark_canals/mechanics/core_mechanics/coreMec_rollResolution|roll]] moves the Difficulty up or down a scale:

| Difficulty  | Success Die |
| ----------- | ----------- |
| `Very Hard` | 6   6       |
| `Hard`      | 5+ 6        |
| `Average`   | 5+ 5+       |
| `Easy`      | 4+ 5+       |
| `Very Easy` | 4+ 4+       |

> [!tip]
> Two factors that have opposite effects cancel each other out. This way, a GM doesn't necessarily need to know all the factors affecting a roll, just whether there is a significant disparity between favorable or detrimental factors.

The [[dark_canals/mechanics/core_mechanics/coreMec_difficulty|Difficulty]] of a roll might also mean actually rolling is not needed:
- If the difficulty is lower than `Very Easy`, the success might be automatic.
- If the difficulty is harder than `Very Hard`, then it is `Impossible`, no matter the result of a roll.

## Difficulty from Opposing Skill
When a [[dark_canals/mechanics/core_mechanics/coreMec_rollResolution|Roll]] is opposed by another Character's [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skill]] (usually an NPC), the base [[dark_canals/mechanics/core_mechanics/coreMec_difficulty|Difficulty]] of that roll is determined by the Character's dice pool in that [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skill]].

| Dice Pool | Skill       | Difficulty  | Success Die |
| --------- | ----------- | ----------- | ----------- |
| 2-3       | `Very Bad`  | `Very Easy` | 6   6       |
| 4         | `Bad`       | `Easy`      | 5+ 6        |
| 5-6       | `Average`   | `Average`   | 5+ 5+       |
| 7-8       | `Good`      | `Hard`      | 4+ 5+       |
| 9-10      | `Very Good` | `Very Hard` | 4+ 4+       |

## Setting the difficulty
Difficulty is affected by factors significant to the action that triggers a roll.

The goals of setting and modifying difficulty are:
- To adjudicate Player decisions with sensible consequences.
- To reward lateral thinking, immersive play and creativity.
- Avoid simple gameplay rewards.

A player's description of the action might impact the difficulty:
- As long as it is not "how good the PC is at a thing" (that is already factored into [[dark_canals/mechanics/core_mechanics/coreMec_profficiencies|Proficiency]] and [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skill]]).
- As long as it is truly significant.

### Items
- Items should not affect Difficulty, but allow actions.
- Using an item as intended should be `Average` Difficulty.
- In some cases, not having a tool means the task is `Hard`, `Very Hard` or `Impossible`.

### Specific Skills
#### Broad Fields & Specialist Skills
If a roll requires specialist knowledge, equipment or training is `Hard` or `Very Hard`.

> As a general rule, those are skills people get paid for.

Some [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skills]] are very broad, and they might contain several subsets or fields of study. This happens specially with [[dark_canals/mechanics/core_mechanics/skills/techne_skill|TECHNE]] and [[dark_canals/mechanics/core_mechanics/skills/reason_skill|REASON]].

> Not every Character with good dice pools in those [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skills]] should be able to apply them with ease in every situation, and comparing Characters with the same dice pools in the skill is not an "apples to apples" comparison.

The difficulty scale for [[dark_canals/mechanics/core_mechanics/skills/techne_skill|TECHNE]] and [[dark_canals/mechanics/core_mechanics/skills/reason_skill|REASON]] is absolute. The difficulty doesn't change from Character to Character, and it is set as "the difficulty for the average person".

> Two high TECHNE Characters might be good at very different activities. They can both attempt each other's specialty at a `Hard` difficulty, just like any other character, and like any other character, they won't have any [[dark_canals/mechanics/core_mechanics/coreMec_profficiencies|Proficiencies]].


#### Niche Skills
Some [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skills]] are niches. Most of the Characters with that skill know the same core concepts, and their dice pool is a simple, linear scale.
The difficulty for those [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skills]] is set in contrast to other activities of that field. The baseline is `Average`.

> For example, [[dark_canals/mechanics/core_mechanics/skills/ballistics_skill|BALLISTICS]] is a pretty specialized field already, so there's no need to make the baseline [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skill]] roll `Hard`. All Characters with good BALLISTICS can shoot better or worse.