---
tags:
  - npc
  - core
aliases:
  - Crossbowman
connections:
  - "[[weapon_crossbow|Crossbow]]"
description: Will defend you against assailants; won’t kill non-combatants, or break the law
npc-type:
  - "[[mechanic_hirelings|Hireling]]"
empathy: 2
wits: 3
agility: 4
strength: 4
skills+:
skills++:
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
- [[hub_armour_leather|Leather Armour]] (full set)
- [[item_mail_coif|Mail Coif]]
- [[item_mail_hauberk|Mail Hauberk]]
- [[weapon_crossbow|Crossbow]]
- [[item_quarrelBoxRegular|Quarrel Box]]