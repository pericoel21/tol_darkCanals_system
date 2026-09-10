---
tags:
  - magic
  - mechanic
  - core
aliases:
  - Spell Difficulty
connections:
  - "[[magic_casting|Casting]]"
description: A spell caster might cast a spell at a different level than the initially calculated one
---
# `= this.file.aliases[0]`
> `= this.description`.

After calculating the [[magic_spellLevel|Spell Level]], a spellcaster might choose to cast the spell at a different level.

| Level Difference | Difficulty   |
| ---------------- | ------------ |
| +3 or higher     | `IMPOSSIBLE` |
| +2               | `VERY HARD`  |
| +1               | `HARD`       |
| Same             | `AVERAGE`    |
| -1               | `EASY`       |
| -2 or lower      | `VERY EASY`  |

## Undercasting
- Each step below the [[magic_spellLevel|Spell Level]] makes the [[mechanic_rollResolution|Roll]] `HARDER` in [[mechanic_difficulty|Difficulty]].
- The benefit is to roll less [[stress die|Stress Dice]], avoiding [[magic_mishaps|Magic Mishaps]].

## Overcasting
- Each step above the [[magic_spellLevel|Spell Level]] makes the [[mechanic_rollResolution|Roll]] `EASIER` in [[mechanic_difficulty|Difficulty]].
- The downside is, more [[stress die|Stress Dice]] are rolled, potentially meaning more [[magic_mishaps|Magic Mishaps]].
