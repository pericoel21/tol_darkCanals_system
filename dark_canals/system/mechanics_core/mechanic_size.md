---
tags:
  - mechanic
  - core
  - metamechanic
aliases:
  - Size
  - Sizes
connections:
description: Scale of sizes used in other mechanics
---
# `= this.file.aliases[0]`
> `= this.description`.

| Tier | Size         | Description                                       | Examples                                        |
| ---- | ------------ | ------------------------------------------------- | ----------------------------------------------- |
| 0    | `TINY`       | Fits in the hand.                                 | Mice, frogs, stoats                             |
| 1    | `SMALL`      | Less than a human.                                | Halflings, goblins, children, dogs, cats        |
| 2    | `MEDIUM`     | Human size.                                       | Adult humans, tigers, black bears               |
| 3    | `LARGE`      | Tops for land, non-monstruous fauna.              | Elephants, grizzly bears, young dragons, trolls |
| 4    | `HUGE`       | One [[combat_distance\|Zone]]. Large for animals. | Hill giants, adult dragons, blue whales         |
| 5    | `GARGANTUAN` | Mitological creatures, small terrain features.    | Ancient dragons.                                |
| 6    | `COLOSAL`    | Landmark terrain features.                        | Kaiju, tarasque                                 |

Use `LARGER` and `SMALLER`.

When casting, if the [[magic_casting#Subject|Subject]] doesn’t already exist (using [[technique_evocation|EVOCATION]] to bring it into existence) it counts as one size higher.

## Creature Size
The size of a creature informs how dangerous it is to het hit by them, but also how hard is to hit them in the first place.
### Getting Attacked
When a creature attacks a target:
- The target's [[mechanic_injury|Injury]] goes up or down in tiers of [[mechanic_intensity|Severity]] equal to the difference in tiers of Size.
- Ergo, `LARGER` creatures receive `LESS SEVERE` [[mechanic_injury|Injuries]].
- That, plus armour, can cause an [[mechanic_injury|Injury]] to be lower than even `1. Minor` tier. That means the target doesn't suffer any [[mechanic_injury|Injury]].

### Hitting a Creature
When a creature is the target and a character attempts to hit it with an attack:
- The [[mechanic_difficulty|Difficulty]] to hit goes up or down in tier equal to the difference in tiers of Size, but in reverse.
- Ergo, `SMALLER` creatures are `HARDER` to hit.
- `IMPOSSIBLE`?

### Example
> A human (medium) with a One-Handed sword would normally cause Severe Injury, but when fighting a troll (large), the same strike counts as Serious Injury, and against a hill giant (huge) only Minor Injury. If the hill giant was wearing leather armour, that Minor Injury wouldn’t even hurt it! If you managed to inflict Critical Injury (counts as Serious because of the size difference) the leather armour would reduce it to a Minor Injury. If this hill giant hit the human with a Severe Injury, it would count as Brutal. Ouch.