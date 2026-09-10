---
tags:
  - item
  - core
  - weapon
aliases:
  - Staff
connections:
description:
weapon-type:
  - Melee
item-size: 4
traits:
  - "[[trait_bashing|Bashing]]"
  - "[[trait_metallic|Wooden]]"
  - "[[trait_oneHanded|One-Handed]]"
injury:
  - "[[mechanic_injury|2. Serious]]"
---
# `= this.file.aliases[0]`
*Weapon Type:* `=this.weapon-type`

> `= this.description`.

| Size         | Handling Trait                                                                                  | Weapon Trait                                                                                  | Other Traits                                                                                                                          | Injury         |
| ------------ | ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| `=this.item-size` | `$= dv.current().traits.filter(t => dv.page(t)["trait-type"]?.includes("handling")).join(", ")` | `$= dv.current().traits.filter(t => dv.page(t)["trait-type"]?.includes("weapon")).join(", ")` | `$= dv.current().traits.filter(t => ["material", "otherTags"].some(w => dv.page(t)["trait-type"]?.join(" ").includes(w))).join(", ")` | `=this.injury` |
