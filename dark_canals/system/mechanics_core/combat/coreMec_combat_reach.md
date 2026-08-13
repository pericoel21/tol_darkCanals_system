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
Reach is the compairson between the length of the [[weapon|Weapons]] being used in a [[coreMec_combat_melee|Melee]].

Usually, [[weapon|Weapons]] indicate their Reach with properties like [[oneHanded|One-Handed]], [[short|Short]], [[long|Long]] or [[heavy|Heavy]].

Being mounted, or the [[sizeCategory|Size Category]] of a character also increases reach by one category.

## Reach & Attacks
- A [[coreMec_combat_melee|Melee Attack]] against someone with greater Reach is performed at a `HARDER` [[coreMec_difficulty|Difficulty]].
- A [[coreMec_combat_melee|Melee Attack]] against someone with lesser Reach is performed at an `EASIER` [[coreMec_difficulty|Difficulty]].

## Closing In
A character might attack an enemy who moves from [[coreMec_combat_distance|Close]] to [[coreMec_combat_distance|Engaged distance]] if they have greater Reach.

The character must be ready, aware and not currently [[coreMec_combat_distance|Engaged]] with an enemy.

The attack caused by Closing In cannot be [[coreMec_combat_reactionsAndCounteractions|Counteracted]] with a [[riposte|Riposte]] or a [[shove|Shove]].
