---
tags:
  - mechanic
  - core
aliases:
  - Item Traits
  - Weapon Traits
  - Traits
connections:
  - "[[weapons_hub|Weapons (Disambiguation)]]"
  - "[[mechanics_meleeWeapons|Melee Weapons]]"
  - "[[mechanics_ranegdWeapons|Ranged Weapons]]"
  - "[[mechanics_guns|Guns]]"
description:
---
# `= this.file.aliases[0]`
> `= this.description`.

Kinds of traits:
- *Combat:* How does a Weapon deal damage
- *Handling:* How does an item get hold while using it. Determines [[mechanic_gear#Size|Size]].
- *Material:* Usually, [[trait_wooden|wood]] or [[trait_metallic|metal]]. Metal rusts, wood does less damage.
- *Condition:* Is the item well maintained? Usable? Or is it [[traits_rusty|rusty]] or [[trait_broken|broken]]?

## Using Traits
When an [[combat_melee|attack’s rating]] equals or exceeds the rating of the [[mechanic_armour|armour]] it hits, if it has the correct Combat Trait for that kind of armour, it also causes that armour to become damaged.
> Like [[trait_piercing|Piercing]] for mail.

The attacker has to specify which Trait are they using for each attack.
> Is it the Piercing point on the end of your lucerne hammer, or the Bashing claw, or are you Hooking them with the hook?

## Creating Items with Traits
### Cost
An item costs one [[mechanic_coin|COIN]] per Trait.

### Creating Weapons
Combining traits it is possible to create a wide variety of weapons. There probably are historical examples for each.

#### Limitations
- Maximum of 3 Traits.
- A single Handling Trait per weapon.

#### Size
A [[trait_oneHanded|one-handed]] weapon is [[mechanic_gear#Size|Size]] 4, a [[trait_short|short]] weapon is [[mechanic_gear#Size|Size]] 2 and a [[trait_heavy|heavy]] or [[trait_long|long]] weapon are both [[mechanic_gear#Size|Size]] 8.

#### Ranged Weapons
- Do not substantially affect armor; do not use Weapon Traits.
- Use specific types of ammo per weapon.

### Wood vs. Metal
- Metal weapons [[trait_rusty|rust]] if not [[mechanic_maintenance|maintained]].
- Wooden weapons

## List of Traits