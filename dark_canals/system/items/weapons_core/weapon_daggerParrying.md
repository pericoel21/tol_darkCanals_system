---
tags:
  - item
  - core
  - weapon
aliases:
  - Parrying Dagger
connections:
description:
weapon-type:
  - Melee
item-size: 2
traits:
  - "[[trait_short|Short]]"
  - "[[trait_piercing|Piercing]]"
  - "[[trait_parrying|Parrying]]"
injury:
  - "[[mechanic_injury|3. Severe]]"
---
# `= this.file.aliases[0]`
*Weapon Type:* `=this.weapon-type`

> `= this.description`.

| Size         | Handling Trait                                                                                  | Weapon Trait                                                                                  | Other Traits                                                                                                                          | Injury         |
| ------------ | ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| `=this.item-size` | `$= dv.current().traits.filter(t => dv.page(t)["trait-type"]?.includes("handling")).join(", ")` | `$= dv.current().traits.filter(t => dv.page(t)["trait-type"]?.includes("weapon")).join(", ")` | `$= dv.current().traits.filter(t => ["material", "otherTags"].some(w => dv.page(t)["trait-type"]?.join(" ").includes(w))).join(", ")` | `=this.injury` |
