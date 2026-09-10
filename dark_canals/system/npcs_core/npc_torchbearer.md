---
tags:
  - npc
  - core
aliases:
  - Torchbearer
connections:
  - "[[hazard_darkness|Darkness]]"
  - "[[item_torch|Torch]]"
description: Stand with you in dark places so you can see without having to hold anything
npc-type:
  - "[[mechanic_hirelings|Hireling]]"
empathy: 3
wits: 4
agility: 4
strength: 3
skills+:
  - "[[skill_mobility|MOBILITY (AGILITY)]]"
skills++:
  - "[[skill_observation|OBSERVATION]]"
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
  - 20 [[item_torch|Torches]]
  - [[item_flintSteel|Flint & Steel]]