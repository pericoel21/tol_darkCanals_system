---
tags:
  - item
  - core
aliases:
  - Cooked Food
connections:
description: Food, spoils.
item-size: 1
stack: 5
---
# `= this.file.aliases[0]`
> `= this.description`.

| Size          | Stack          |
| ------------- | -------------- |
| `= this.item-size` | `= this.stack` |

- Spoils at the end of the day.
- Can be created by [[mechanic_cooking|Cooking]].
- Can be [[mechanic_preservingFood|preserved]] into [[item_ration|Food Rations]].
- When [[mechanic_preservingFood|Preserving Food]], any amount not preserved successfully still converts into Cooked Food.
