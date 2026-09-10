---
tags:
  - core
  - mechanic
  - item
aliases:
  - Torches
  - Torch
connections:
description: Provide low light in close range and can help make campfires
item-size: 1
stack: 5
kit:
  - "[[item_kit_dungeoneer|Dungeoneer's Kit]]"
---
# `= this.file.aliases[0]`
> `= this.description`.

| Size          | Stack          |
| ------------- | -------------- |
| `= this.item-size` | `= this.stack` |

## Torch Light
- By itself, it is [[hazard_darkness|low light]] up to `CLOSE` [[combat_distance|distance]].
- Torches help **reduce the [[mechanic_difficulty|Difficulty]] of [[hazard_darkness|Darkness]]** by one step each.
- In a dungeon, one torch makes most rolls `HARD`, and two, `AVERAGE`.

## Camping in a Bare Place
In some places (like deserts or dungeons), there are no **available materials to make a fire** when [[mechanic_makingCamp|Camping]]. **Torches must be used,** instead.

For **each torch** used to create a campfire, it provides enough **heat for that many people for a [[mechanic_watches|Watch]].**

> Unlike in the wilderness where fires can be made from scavenged materials, in a dungeon you use torches. 