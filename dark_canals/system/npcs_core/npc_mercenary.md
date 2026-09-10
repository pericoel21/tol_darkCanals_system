---
tags:
  - npc
  - core
aliases:
  - Mercenary
connections:
description: Will defend you against assailants, and cover your retreat; won’t kill non-combatants, or break the law
npc-type:
  - "[[mechanic_hirelings|Hireling]]"
empathy: 2
wits: 3
agility: 4
strength: 4
skills+:
  - "[[skill_physique|PHYSIQUE (STRENGTH)]]"
skills++:
  - "[[skill_fight|FIGHT (STRENGTH)]]"
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
- [[hub_armour_leather|Leather Armour]] (full set)
- [[item_plate_breast|Breastplate]]
- [[item_plate_helm|Helm]]
- [[trait_oneHanded|One-Handed]] weapon, one of:
	1.  [[weapon_swordArming|Arming Sword]]
	2.  [[weapon_mace|Mace]]
	3. [[weapon_hammerWar|Warhammer]]
- [[shield_shieldRegular|Shield]]
- [[weapon_daggerRondel|Rondel Dagger]]