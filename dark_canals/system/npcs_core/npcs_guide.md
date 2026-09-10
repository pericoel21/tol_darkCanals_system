---
tags:
  - npc
  - core
aliases:
  - Guide
connections:
  - "[[weather]]"
  - "[[mechanic_overlandTravel|Overland Travel]]"
  - "[[mechanic_makingCamp|Making Camp]]"
  - "[[hazard_darkness|Darkness]]"
description: Will set up camp for you in the wilderness, while they are with you, you are not slowed by difficult terrain, darkness or inclement weather
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