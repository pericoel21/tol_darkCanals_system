---
tags:
  - mechanic
  - core
  - metamechanic
aliases:
  - Gear
  - Inventory
connections:
  - "[[phi_gear|Gear vs. proficiencies & bonuses]]"
description: Gear, its general properties, and how it is managed in the inventory
---
# `= this.file.aliases[0]`
> `= this.description`.

## Gear Properties
### Size
Number of squares in the inventory that the piece of gear takes.
- Defined by a single number, gear is always a line of squares.
- Can be fitted horizontally or vertically.

#### Tiny Items (Trinkets)
Items that fit in an enclosed fist.
Fit as many as possible in free boxes in the inventory. Must be legible.

### Stackables
Items that can be stored more efficiently by packing same things together.
Keep more than one of them in the same slot, up to the maximum of their stack size.

## Consumables
Consumables are presented as full stacks. When a consumable is shown in a table or in the book, the accompanying number is the number of uses or individual items the stack comes with.
> [[item_waterskin|Waterskin]] (5) means a single [[item_waterskin|waterskin]] contains 5 rations of [[water|water]].

### Tracking Consumables
Use the small fields in the inventory to track properties like rust, damage, number of arrows in a quiver, maximum stacks, amounts...

## Backpack vs. Inventory
The inventory is always accesible to a character.
To access the [[item_backpack|backpack]], it must be taken off, and the character must be stationary.

## Gear, Skills and Possible Activities
- In most cases, gear facilitates an activity because the item is meant for that activity, not because of the stats of that item.
- Some gear depend on a specific [[mechanic_skills|Skill]]. How skilled the person is, is a bigger factor than the quality of the gear.
> [[skill_ballistics|BALLISTICS (AGILITY)]] is a bigger factor than the quality of the [[item_shortBow|bow]].
- Some gear makes an activity `EASIER`, or even possible at all.