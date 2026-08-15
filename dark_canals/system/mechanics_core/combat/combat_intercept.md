---
tags:
  - combat
  - core
  - mechanic
aliases:
  - Intercepting
  - Intercept
connections:
description: A character might interpose themselves between an ally and an incoming attack
---
# `= this.file.aliases[0]`
> `= this.description`.

A character might perform a [[reactions_dodge|DODGE]], [[reactions_parry|PARRY]] or [[reactions_block|BLOCK]] [[combat_reactionsAndCounteractions|Reaction]] when someone other than themsef is targeted by a [[combat_melee|Melee attack]].

## Requisites
- Be in the **same [[combat_distance|Zone]].**
- **Not be in [[combat_distance|Engaged Range]]** with other active combatant.
- It counts as breaking turn order. A **[[stat_stamina|Stamina]] must be spent.**
- **[[combat_ranged|Ranged Attacks]]** cannot be [[reactions_parry|PARRIED]].

## Result of the roll
### On a Success
- [[reactions_parry|PARRY]] and [[reactions_block|BLOCK]] work as usual.
- **[[reactions_dodge|DODGE]] causes a [[combat_melee#Result of the Attack Roll|Full hit]]** on the PC who Intercepts.

### On a Failure
- Character who Intercepts **still moves.**
- Attack is **resolved as normal** against the original target.