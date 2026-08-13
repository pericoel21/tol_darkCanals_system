---
tags:
  - combat
  - core
  - mechanic
aliases:
  - Grappling
  - Grapple
connections:
description: Grappling enemies allows for attacks that bypass their armor
---
# `= this.file.aliases[0]`
> `= this.description`.

## Going for the Grapple
- Can be attempted at [[coreMec_combat_distance|Close Distance]].
- Performed with a [[skill_mobility|MOBILITY]] [[coreMec_rollResolution|Roll]] or a [[couteraction_manoeuvre|MANOEUVRE Counteraction]].

### Result of a Grapple Roll

| Roll            | Result                                      |
| --------------- | ------------------------------------------- |
| Full Success    | Grapple succeeds (see below)                |
| Partial Success | Failed to initiate, no negative consequence |
| Failure         | Only attacker falls [[prone\|Prone]]        |
### Successful Grapple
- **Both** attacker and target are **[[prone|Prone]].**
- **Neither can move** from their current position.

## Acting while Grappling
### Escaping a Grapple
- Roll **[[skill_physique|PHYSIQUE]] or [[skill_mobility|MOBILITY]] against opponent's [[skill_physique|PHYSIQUE]].**
- *Success:* Character is in [[coreMec_combat_distance|Engaged Range]] and **no longer grappled.**

### Attacking
- **Unarmed** [[skill_fight|FIGHT]] attacks **ignore [[coreMec_armour|Armour]].**
- Weapons larger than a dagger **(not [[traits_short|SHORT]])** are difficult to use: **Only cause [[coreMec_injury|Minor Injuries]].**
- [[traits_short|SHORT]] [[weapon|Weapons]] **ignore [[item_plateArmour|Plate Armour]].**

### Chokehold
While grappling, [[coreMec_rollResolution|roll]] [[skill_fight|FIGHT]] to lock the opponent in a chokehold.
Success:
- Causes no [[coreMec_injury|Injuries]].
- Opponent **can only act to try to escape,** as an [[coreMec_opposedRolls|Opposed Roll]].

### Other actions
Attempt anything other than attacking each other: Opposed roll of [[skill_physique|PHYSIQUE]] vs. [[skill_physique|PHYSIQUE]]. Winner either accomplishes what they were doing, or stops the other from doing what they were doing.