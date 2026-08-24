---
tags:
  - core
  - mechanic
aliases:
  - Healing
  - Natural Healing
  - Mediacal Care
connections:
description: Natural healing is slow, and surgery is complicated or expensive
---
# `= this.file.aliases[0]`
> `= this.description`.

## Natural Healing
If a character has any [[mechanic_injury|Injury]], at the beginning of each week they roll [[skill_endure|ENDURE]].
- When an [[mechanic_injury|Injury]] is healed, it is downgraded one step.
- When a `MINOR` [[mechanic_injury|Injury]] is downgraded, it heals completely.

The level of [[mechanic_injury|Injury]] that is healed depends on the [[mechanic_difficulty|Difficulty]] of the roll:
- [[mechanic_rollResolution|Roll]] [[skill_endure|ENDURE]] just once.
- Compare the result to the [[mechanic_difficulty|Difficulty]] of the highest wound.
- Reduce [[mechanic_difficulty|Difficulty]] for each day of the previous week where the character did nothing but to rest.
- Minimum [[mechanic_difficulty|Difficulty]] is `VERY EASY`.

| [[mechanic_difficulty\|Difficulty]] | [[mechanic_injury\|Injury]] downgraded   |
| ----------------------------------- | ---------------------------------------- |
| `VERY EASY`                         | `MINOR`                                  |
| `EASY`                              | `MINOR`, `SERIOUS`                       |
| `AVERAGE`                           | `MINOR`, `SERIOUS`, `SEVERE`             |
| `HARD`                              | `MINOR`, `SERIOUS`, `SEVERE`, `CRITICAL` |

## Medical Care
When a character provides Medical Care:
1. Pick a [[combat_hitLocations|Hit Location]].
2. Use Natural Healing [[mechanic_difficulty|Difficulty]].
3. Use required items & time.
	- Using additional items decreases [[mechanic_difficulty|Difficulty]] to a minimum of `VERY EASY` (even after failing, see [[mechanic_crafting|Crafting]]).
	- Performing surgery in one self is `HARDER`.
	- [[skill_surgery|SURGERY]] in [[mechanic_settlements|Settlements]] by NPCs cost one [[mechanic_coin|COIN]] but auto-succeeds.



| [[mechanic_injury\|Injury Level]] | Item needed                                                                                     | Time spent |
| --------------------------------- | ----------------------------------------------------------------------------------------------- | ---------- |
| `MINOR`                           | [[item_bandages\|Bandages]] (get used)                                                          | 10min      |
| `SERIOUS`                         | [[item_bandages\|Bandages]] (get used)                                                          | 10min      |
| `SEVERE`                          | [[item_surgicalSupplies\|Surgical Supplies]] (get used), [[item_surgicalTools\|Surgical Tools]] | 1h         |
| `CRITICAL`                        | [[item_surgicalSupplies\|Surgical Supplies]] (get used), [[item_surgicalTools\|Surgical Tools]] | 1h         |

