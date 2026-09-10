---
tags:
  - mechanic
  - core
aliases:
  - NPC Creation
connections:
description: NPCs have the same fields as PCs, but they are usually used to define difficulties instead of rolling
---
# `= this.file.aliases[0]`
> `= this.description`.

## Stats
### [[mechanic_attributes|Attributes]]
From 1 to 5.

| Attribute | Meaning    |
| --------- | ---------- |
| 1         | `CRIPPLED` |
| 2, 3      | `VERY BAD` |
| 4         | `BAD`      |
| 5         | `AVERAGE`  |

### [[mechanic_skills|Skills]]
- Handled with `+` and `++`, meaning the specific skill is one or two levels higher than the corresponding attribute.
- [[mechanic_difficulty|Difficulty]] is what gets used 90% of the time.
- Dice Pool is what the NPC would roll if a player facing roll is not possible.

| Skill       | Difficulty  | Dice Pool |
| ----------- | ----------- | --------- |
| `VERY BAD`  | `VERY EASY` | 2         |
| `BAD`       | `EASY`      | 4         |
| `AVERAGE`   | `AVERAGE`   | 6         |
| `GOOD`      | `HARD`      | 8         |
| `VERY GOOD` | `VERY HARD` | 10        |

## Statting People
People are usually `Medium` [[mechanic_size|Size]]

### Attributes & Skills
Starting point:
- Array for [[mechanic_attributes|Attributes]]: `4, 4, 3, 3`.
- Two [[mechanic_skills|Skills]] with `+`.

Tweaks:
- Increase one [[mechanic_attributes|Attribute]] and decrease another.
- Attributes have a minimum of 2 and a maximum of 5.
- Decrease an [[mechanic_attributes|Attribute]] by 1 to gain two `+`s or one `++`.

> An average fighter should be `AVERAGE` at `FIGHT`ing, an average person is `BAD` at everything. A guy with 5 in, say, `STRENGTH`, should be, like, the tribe’s strongest guy, not just a regular kind of guy!

#### Social Skills
Only do this step once the NPC needs actually use social [[mechanic_skills|Skills]], like when [[mechanic_interrogation|Pressing for Information or Assessing Personality]].

Mainly:
- [[skill_endure|ENDURE (STRENGTH)]] to resist intimidation.
- [[skill_insight|INSIGHT (EMPATHY)]] to resist appeal to emotion.
- [[skill_reason|REASON (WITS)]] to resist appeal to logic.

Assume they are `BAD` at one, `GOOD` at other, and `AVERAGE` at the remaining one.

![[mechanic_interrogation#Describing Characters Based on Social Skills]]

### Stamina & Resolve
The sum of [[stat_stamina|Stamina]] & [[stat_resolve|Resolve]] should be 10.

| If...                                                                  | Stamina | Resolve |
| ---------------------------------------------------------------------- | ------- | ------- |
| [[attribute_strength\|STRENGTH]] + [[attribute_agility\|AGILITY]] >= 9 | 6       | 4       |
| [[attribute_wits\|WITS]] + [[attribute_empathy\|EMPATHY]] >= 9         | 4       | 6       |
| Else                                                                   | 5       | 5       |

### Gear
- Whatever [[mechanic_gear|Gear]] is logical they would have.
- Get inspired by art, minis...
- Careful with [[hub_armour_plate|Plate Armour]]: Very OP
- A good starting point is to have a [[item_kit_starter|Starter Kit]].
- Give a [[item_kit_survivalist|Survivalist Kit]] to NPCs who are supposed to go camoing or adventuring around the world.
- Use a [[item_kit|Kit]] that fits with their proffession.

## Statting Creatures
Start by choosing an adecuate [[mechanic_size|Size]].

[[mechanic_attributes|Attributes]] & [[mechanic_skills|Skills]]
- They might not need [[attribute_empathy|EMPATHY]] or [[attribute_wits|WITS]].
- Go freeform with [[attribute_strength|STRENGTH]] and [[attribute_agility|AGILITY]], from 1 to 5

### [[mechanic_naturalArmour|Natural Armour]]
- Select a single type of natural armour unless there's good reason for it.
- Specify the level of [[mechanic_injury|Injury]] it protects from.
- Different [[combat_hitLocations|Hit Locations]] may have different levels of [[mechanic_injury|Injury]], even if the same kind of armour applies.

### Weapons (natural or not)
- As a guide, predators with sharp claws are probably going to cause `3. Severe` [[mechanic_injury|Injuries]].
- Some specific things (a giant scorpion’s tail, perhaps) would be `4. Critical`.
- For actual weapons, give the creature the correct size of weapon they'd use and check [[mechanics_weaponSizes|Weapon Sizes]].

### [[combat_hitLocations|Hit Locations]]
- Create a custom D6 table.
- Or, use arms as upper or forward appendages, legs for rear or lower appendages, torso for the main bulk of the creature and head as it’s head, or other weak spot.
- Keep in mind that `Head` is the harder part to hit.
- Some locations might not be reachable if the [[mechanic_size|Size]] of the creature is too big (or a [[trait_thrown|Long weapon]] might be needed).
- Check [[combat_weakSpots|Weak Spots]].

### [[mechanic_creatureTraits|Traits]]
- Every creature has a special, unique quality. They break the rules of the world.
- They shoud be created in a bespoke way, the list of creature traits are guidelines.
- They should be easy to put into natural, narrative language, a description that would happen in-world.
- Avoid traits that affect the PC's authonomy:
	- Target [[mechanic_conditions|Conditions]] instead of draining [[stat_stamina|Stamina]] or [[stat_resolve|Resolve]].

## Tracking NPCs
- Use the NPC tracker sheet during combats.
- It is designed so not much needs filling, motsly, it is crossing stuff out.
- Cross stuff above the maximum.
	- No difference between no having armour at a level, and having it damaged.
- Make a line between [[stat_stamina|Stamina]] and [[stat_resolve|Resolve]] where it needs to be.
- [[mechanic_injury|Injuries]] work exactly like with PCs.
	- Critical injuries usually take down an NPC.
	- If not, mark the border of the Severe Injury.
- [[mechanic_attributeDamage|Attribute Damage]] and depletion works like PCs.
	- If an [[mechanic_attributes|Attribute]] reaches 0, the NPC will probably attempt to flee.