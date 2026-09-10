---
tags:
  - npc
  - core
aliases:
  - Horse Handler
connections:
  - "[[mechanic_horse|Horse]]"
description: While you have a horse handler, your horses will always be fed and watered, and they will move your horses away from danger
npc-type:
  - "[[mechanic_hirelings|Hireling]]"
empathy: 4
wits: 4
agility: 3
strength: 3
skills+:
  - "[[skill_endure|ENDURE (STRENGTH)]]"
skills++:
  - "[[skill_appeal|APPEAL (EMPATHY)]]"
skills+++:
inventory:
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
- [[item_horseFood|Horse Food]]