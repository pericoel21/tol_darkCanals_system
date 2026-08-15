---
tags:
  - combat
  - core
  - mechanic
aliases:
  - Reach
connections:
description: A longer reach in melee attacks gives a character the edge in combat
---
# `= this.file.aliases[0]`
> `= this.description`.

## Definition
Reach is the compairson between the length of the [[item_weapon|Weapons]] being used in a [[combat_melee|Melee]].

Usually, [[item_weapon|Weapons]] indicate their Reach with properties like [[traits_oneHanded|One-Handed]], [[traits_short|Short]], [[traits_long|Long]] or [[traits_heavy|Heavy]].

Being mounted, or the [[sizeCategory|Size Category]] of a character also increases reach by one category.

## Reach & Attacks
- A [[combat_melee|Melee Attack]] against someone with greater Reach is performed at a `HARDER` [[mechanic_difficulty|Difficulty]].
- A [[combat_melee|Melee Attack]] against someone with lesser Reach is performed at an `EASIER` [[mechanic_difficulty|Difficulty]].

## Closing In
A character might attack an enemy who moves from [[combat_distance|Close]] to [[combat_distance|Engaged distance]] if they have greater Reach.

The character must be ready, aware and not currently [[combat_distance|Engaged]] with an enemy.

The attack caused by Closing In cannot be [[combat_reactionsAndCounteractions|Counteracted]] with a [[couteraction_riposte|RIPOSTE]] or a [[couteraction_shove|SHOVE]].
