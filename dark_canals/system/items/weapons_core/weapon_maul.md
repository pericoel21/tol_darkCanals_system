---
tags:
  - item
  - core
  - weapon
aliases:
  - Maul
connections:
description:
item-size: 8
traits:
  - "[[trait_heavy|Heavy]]"
  - "[[trait_bashing|Bashing]]"
injury:
  - "[[mechanic_injury|4. Critical]]"
weapon-type:
  - Melee
---
# `= this.file.aliases[0]`
*Weapon Type:* `=this.weapon-type`

> `= this.description`.

| Size         | Handling Trait                                                                                  | Weapon Trait                                                                                  | Other Traits                                                                                                                          | Injury         |
| ------------ | ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| `=this.item-size` | `$= dv.current().traits.filter(t => dv.page(t)["trait-type"]?.includes("handling")).join(", ")` | `$= dv.current().traits.filter(t => dv.page(t)["trait-type"]?.includes("weapon")).join(", ")` | `$= dv.current().traits.filter(t => ["material", "otherTags"].some(w => dv.page(t)["trait-type"]?.join(" ").includes(w))).join(", ")` | `=this.injury` |
