---
tags:
  - core
  - mechanic
aliases:
  - Foraging & Hunting
  - Foraging
  - Huting
  - Fishing
  - Trapping
connections:
description: Use one roll to forage for scrap or food, fishing, hunting...
---
# `= this.file.aliases[0]`
> `= this.description`.


Foraging or Hunting takes one [[coreMec_watches|Watch]].
Roll an appropriate [[coreMec_skills|Skill]], with a [[coreMec_difficulty|Difficulty]] determined by the biome. 

On a Success, the PC finds one portion of the resource they were looking for. Each [[coreMec_degreesOfSuccess|Degree of Success]] adds one portion to the quantity found.
On a Failure, the GM rolls for a [[random wilderness encounters|Random Encounter]].

## Actions, Skills & Goods Obatined

| Action                 | Skill                              | Resulting Goods                                                    |
| ---------------------- | ---------------------------------- | ------------------------------------------------------------------ |
| Foraging               | [[skill_observation\|OBSERVATION]] | Wood or Plant [[coreMec_crafting\|Scrap]]; pipeweed, edible plants |
| Fishing (with rod)     | [[skill_techne\|TECHNE]]           | Raw food                                                           |
| Trapping (with snares) | [[skill_techne\|TECHNE]]           | Raw food, Animal [[coreMec_crafting\|Scrap]]                       |
| Hunting                | [[skill_ballistics\|BALLISTICS]]]  | Raw food, Animal [[coreMec_crafting\|Scrap]]                       |

## Biome vs. Difficulty
Fishing is `VERY EASY` when the biome is costal or near a large body of water.

| Biome                  | Foraging    | Fishing      | Trapping    | Hunting     |
| ---------------------- | ----------- | ------------ | ----------- | ----------- |
| Desert                 | `HARD`      | `IMPOSSIBLE` | `AVERAGE`   | `HARD`      |
| Forest, plains, jungle | `VERY EASY` | `VERY EASY`  | `VERY EASY` | `VERY EASY` |
| Tundra, mountains      | `HARD`      | `AVERAGE`    | `EASY`      | `EASY`      |
| Underground            | `EASY`      | `AVERAGE`    | `EASY`      | `HARD`      |
