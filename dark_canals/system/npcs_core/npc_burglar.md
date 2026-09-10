---
tags:
  - npc
  - core
aliases:
  - Burglar
connections:
description: Will pick locks, only steals from the long dead
npc-type:
  - "[[mechanic_hirelings|Hireling]]"
empathy: 3
wits: 3
agility: 4
strength: 3
skills+:
  - "[[skill_mobility|MOBILITY (AGILITY)]]"
skills++:
  - "[[skill_techne|TECHNE (AGILITY)]]"
skills+++:
size: Medium
---
# `= this.file.aliases[0]`

| Type         | Size         |
| ------------ | ------------ |
| `=this.type` | `=this.size` |


> `= this.description`.

| EMP             | WIT          | AGI             | STR              |
| --------------- | ------------ | --------------- | ---------------- |
| `=this.empathy` | `=this.wits` | `=this.agility` | `=this.strength` |

`$= dv.current()["skills+"]?.map(t => t + " +").join(", ") ?? ""`
`$= dv.current()["skills++"]?.map(t => t + " ++").join(", ") ?? ""`
`$= dv.current()["skills+++"]?.map(t => t + " +++").join(", ") ?? ""`

## Inventory
  - [[item_starterKit|Starter Kit]]
  - [[item_survivalistKit|Survivalist Kit]]
  - [[item_thievesKit|Thieves' Kit]]
  - [[hub_armour_leather|Leather Armour]] (full set)
  - [[weapon_daggerParrying|Dagger]]