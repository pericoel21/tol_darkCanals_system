---
tags:
  - core
  - mechanic
aliases:
  - Opposed Rolls
connections:
description: Methods of rolling in opposition to another character
---
# `= this.file.aliases[0]`
> `= this.description`.

## Factor for Difficulty
When a [[mechanic_rollResolution|Roll]] is opposed by another Character's [[mechanic_skills|Skill]] (usually an NPC), the base [[mechanic_difficulty|Difficulty]] of that roll is determined by the Character's dice pool in that [[mechanic_skills|Skill]].

### Dice Pool v. Difficulty Relation

| Dice Pool | Skill       | Difficulty  | Success Die |
| --------- | ----------- | ----------- | ----------- |
| 2-3       | `Very Bad`  | `Very Easy` | 6   6       |
| 4         | `Bad`       | `Easy`      | 5+ 6        |
| 5-6       | `Average`   | `Average`   | 5+ 5+       |
| 7-8       | `Good`      | `Hard`      | 4+ 5+       |
| 9-10      | `Very Good` | `Very Hard` | 4+ 4+       |

## Actual Opposed Rolls
Using actual opposed rolls is possible and doesn't break the game.
1. Both Characters roll.
2. If only one of the rolls is a success, it is the winner. 
3. In any other case, the [[mechanic_degreesOfSuccess|Degrees of Success]] are compared.

> [!danger] Bogging Down the Game
> Doing actual opposed rolls can lead down to ties. Even without a tie, the process is slower than using a dice pool as a base Difficulty.
