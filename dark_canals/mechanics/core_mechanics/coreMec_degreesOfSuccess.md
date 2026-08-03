---
tags:
  - core
  - mechanic
aliases:
  - Degrees of Success
connections:
description: Quantification of roll outcomes (ouside the binary success / failure)
---
# `= this.file.aliases[0]`
> `= this.description`.

The Degrees of Success of a [[coreMec_rollResolution|Roll]] are determined by comparing the `Success Dice` to the requirements given by the [[coreMec_difficulty|Difficulty]].
- Degreees of success range from -2 to 2, and it can be 0.
- They are how many dice are over the Difficulty requirements when a roll succeeds (granting positive Degrees), or under the Difficulty on a failed roll (accounting for negative Degrees). If a roll exactly meets the Difficulty, it succeeds, but has 0 Degrees.
- In certain situations, a roll with 0 Degrees of Success represents success, but with some kind of cost, consequence or setback.

| Degrees | Success Dice            |
| ------- | ----------------------- |
| 2       | Both exceed Difficulty  |
| 1       | One exceeds Difficulty  |
| 0       | Exactly meet Difficulty |
| -1      | One below Difficulty    |
| -2      | Both below Difficulty   |



> [!danger] Bogging down the game
> Use Degrees of Success only when it really matters as to not slow down the game too much. Try to avoid them if a simple binary outcome is enough (success or fail).