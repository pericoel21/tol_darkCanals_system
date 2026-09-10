---
tags:
  - mechanic
  - core
aliases:
  - Natural Armour
connections:
description: Creatures might be protected by somethin akin to armour, that can be statted similarly
---
# `= this.file.aliases[0]`
> `= this.description`.

- Usually, creatures only have one type of armour.
- The type of natural armour defines what [[mechanic_itemTraits|weapon Traits]] affect them.
- A type of natural armour doesn't always need to have the same level of [[mechanic_injury|Injury]] all across the creature, or in several creatures.
- Therefore, the level of [[mechanic_injury|Injury]] for the armour is always specified.

## Correspondance to Armour
In terms of traits, natural armour can be compared to the typical types of humanoid armour:

| Natural                                                                                       | Equivalent                      |
| --------------------------------------------------------------------------------------------- | ------------------------------- |
| [[hub_armour_hide\|Hide]]                                                                     | [[hub_armour_leather\|Leather]] |
| [[hub_armour_scales\|Scales]]                                                                 | [[hub_armour_mail\|Mail]]       |
| [[hub_armour_bone\|Bone]], [[hub_armour_plastron\|plastron]] or [[hub_armour_chitin\|chitin]] | [[hub_armour_plate\|Plate]]     |

## Example
> An insectoid might have Plate (I), meaning their natural armour is still Damaged by Bashing weapons, but only reduces Injury by 1. Because the difference in creature size reduces the level of Injury inflicted, a large creature with Scales (II) would require an attack which would normally cause Critical Injury to Damage their scales (for example, a full hit with an Estoc). To fight a Huge scaled creature? You’d need to hit that guy for a heavy hit with your Estoc!

> Perhaps a dragon is covered in Scales (II), save for a weak spot on their undercarriage that is Scales (I).