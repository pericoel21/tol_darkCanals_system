---
tags:
aliases:
  - Random Encounters & Wandering Monsters
  - Random Encounters
  - Wandering Monsters
  - Dice Pool of Doom
connections:
  - "[[mechanics_weather|Weather]]"
description: Random encounters help put pressure on time
---
# `= this.file.aliases[0]`
> `= this.description`.

## When to Roll
- For every [[mechanic_overlandTravel|league of travel]].
- When spending the night in the wilderness.
- When [[mechanic_overlandTravel#Looking for Something|searching]] an area (on a failed roll).
- Every 10, 20 or 30 minutes in a dungeon (depending on danger level).
- Every time the party is noisy in a dungeon.
- When [[mechanic_makingCamp|Making Camp]] in a dungeon.

Do not roll in [[mechanic_settlements|Settlements]]

## Parsing the Result
Ignore results if in some specific situations

| Ignore                                    | If                                                        |
| ----------------------------------------- | --------------------------------------------------------- |
| All results (don't roll)                  | In [[mechanic_settlements\|Settlements]]                  |
| All except creatures                      | In a Dungeon                                              |
| Locations and [[hazard_general\|Hazards]] | Travelling by road<br>When camping<br>On a return journey |

### Distance
How far away is the encounter when characters notice.

#### Ambush
- If it is `SHORT`, `CLOSE` or `ENGAGED` for a hostile, it is an attempt to ambush.
- The further away, the `EASIER` the [[skill_observation|OBSERVATION (WITS)]] roll to avoid the ambush.
- Check [[mechanic_stealth|Sneaking]].

## Avoiding Encounters
- If characters see it coming, they can avoid a specific encounter, adding [[mechanic_overlandTravel|one league]] to the distance needed.
- A party can travel carefuly, automatically adding [[mechanic_overlandTravel|one league]] per encounter.

## How to Roll, aka. Dice Pool of Doom
Pool of 5D6:
1. Kind of thing / encounter
2. How far
3. [[mechanics_npcUse#Disposition|Disposition]]
4. Subset of the thing / encounter
5. Specific thing within subset

Roll them in order, so any type of encounter that is not releveant doesn't get rolled further.