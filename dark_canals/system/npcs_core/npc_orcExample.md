---
tags:
  - npc
  - core
aliases:
  - Orc
connections:
description: Example in NPC page
npc-type:
empathy: 3
wits: 3
agility: 4
strength: 4
skills+:
  - "[[skill_physique|PHYSIQUE (STRENGTH)]]"
  - "[[skill_fight|FIGHT (STRENGTH)]]"
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

Either:
- [[shield_shieldRegular|Shield]]
- [[weapon_axeSparth|Sparth Axe]]
Or:
- [[weapon_axeBattle|Battle-Axe]]