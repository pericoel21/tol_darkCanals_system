---
tags:
  - magic
  - mechanic
  - core
aliases:
  - Spell Level
connections:
description: Determines if a character is able to cast the spell at all, and how many stress dice they include
---
# `= this.file.aliases[0]`
> `= this.description`.

## Level & Casting
When [[magic_casting|Casting]] a spell:
- The Level of the Spell cannot be higher than the caster's relevant [[mechanic_skills|Skill]].
	 - Note: not the whole dice pool, but only the [[mechanic_skills|Skill]] used as part of it.
- The Level of the Spell determines the amount of [[stress die|Stress Die]] used in the [[mechanic_rollResolution|Roll]].

## Factoring the Spell Level
Increasing the spell’s size, moving something a longer distance, increasing the effect’s intensity and increasing the complexity of the Form of the spell all increase the spell’s Level.

### Factors of Spell level

| Level / # Targets | [[mechanics_size\|Size]]              | [[combat_distance\|Distance]] | [[mechanic_intensity\|Intensity]] | [[mechanic_complexity\|Complexity]] |
| ----------------- | ------------------------------------- | ----------------------------- | --------------------------------- | ----------------------------------- |
| 0                 | `TINY`                                | None / `Engaged`              | Illusory                          | `ELEMENTAL`                         |
| 1                 | `SMALL`                               | `CLOSE`                       | `MINOR`                           | `SIMPLE`                            |
| 2                 | `MEDIUM`                              | `SHORT`                       | `SERIOUS`                         | `MODERATE`                          |
| 3                 | `LARGE`                               | `LONG`                        | `SEVERE`                          | `INTRICATE`                         |
| 4                 | `HUGHE` / 1 [[combat_distance\|Zone]] | `FAR`                         | `CRITICAL`                        | `INCOMPREHENSIBLE`                  |

### Changes to the Table
- If the [[magic_casting#Subject|Subject]] doesn’t already exist, using [[technique_evocation|EVOCATION]] to bring it into existence counts as one size `Larger`.
- When [[magic_aimingShooting|Shooting with Magic]], the number of possible targets (not [[magic_casting#Subject vs. Target|Subjects]]) corresponds to the Level column.
- The [[combat_distance|Distance]] column is only relevant for spells that are [[magic_aimingShooting|Shot]]. (Distance to [[magic_casting#Subject|Subject]] is irrelevant as long as it is visible).
