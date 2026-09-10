---
tags:
  - item
  - core
  - mechanic
aliases:
  - Raw Food
  - Raw Meat
connections:
  - "[[mechanic_cooking|Cooking]]"
  - "[[mechanic_preservingFood|Preserving Food]]"
  - "[[mechanic_tanning|Tanning]]"
description: Raw food goes bad after a day
item-size: 1
stack: 5
kit:
traits:
  - "[[trait_perishable|Perishable]]"
---
# `= this.file.aliases[0]`
> `= this.description`.

| Size          | Stack          |
| ------------- | -------------- |
| `= this.item-size` | `= this.stack` |

![[trait_perishable]]

## Uses
- [[mechanic_cooking|Cooking]]
- [[mechanic_preservingFood|Preserving]]
- [[mechanic_tanning|Tanning]]: Turn portions of Raw Meat (specifically) into Leather [[mechanic_crafting|Scraps]]