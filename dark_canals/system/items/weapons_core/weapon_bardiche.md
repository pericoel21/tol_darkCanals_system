---
tags:
  - item
  - core
  - weapon
aliases:
  - Bardiche
connections:
description:
weapon-type:
  - Melee
item-size: 8
traits:
  - "[[trait_hacking|Hacking]]"
  - "[[trait_piercing|Piercing]]"
  - "[[trait_heavy|Heavy]]"
injury:
  - "[[mechanic_injury|4. Critical]]"
---
# `= this.file.aliases[0]`
*Weapon Type:* `=this.weapon-type`

> `= this.description`.

| Size         | Handling Trait                                                                                  | Weapon Trait                                                                                  | Other Traits                                                                                                                          | Injury         |
| ------------ | ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| `=this.item-size` | `$= dv.current().traits.filter(t => dv.page(t)["trait-type"]?.includes("handling")).join(", ")` | `$= dv.current().traits.filter(t => dv.page(t)["trait-type"]?.includes("weapon")).join(", ")` | `$= dv.current().traits.filter(t => ["material", "otherTags"].some(w => dv.page(t)["trait-type"]?.join(" ").includes(w))).join(", ")` | `=this.injury` |
