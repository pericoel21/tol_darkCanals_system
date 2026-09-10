---
tags:
  - npc
  - core
aliases:
  - Porter
connections:
description: Keeps a backpack for the party, and will follow them; retreats to safety if there’s danger
npc-type:
  - "[[mechanic_hirelings|Hireling]]"
empathy: 3
wits: 3
agility: 4
strength: 4
skills+:
  - "[[skill_mobility|MOBILITY (AGILITY)]]"
  - "[[skill_physique|PHYSIQUE (STRENGTH)]]"
skills++:
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
  - [[item_backpack|Backpack]] (Empty)
  - [[item_starterKit|Starter Kit]]
  - [[item_survivalistKit|Survivalist Kit]]