---
tags:
aliases:
  - Injury
  - Minor Injury
  - Serious Injury
  - Severe Injury
  - Critical Injury
  - Brutal Injury
connections:
description: Each injury affects a location, and has an effect that depends on its level of severity
---
# `= this.file.aliases[0]`
> `= this.description`.

## Injury Levels
All Effects for one level includes the effects of previous levels. 

| Lvl. | Injury   | Examples                                                                            | Effects                                               | Cause                 |
| ---- | -------- | ----------------------------------------------------------------------------------- | ----------------------------------------------------- | --------------------- |
| 1    | Minor    | Cuts, bruising, abrasions.                                                          | None.                                                 | Unarmed attacks       |
| 2    | Serious  | Puncture wounds, bleeding, soft tissue damage, torn muscles.                        | Causes [[coreMec_attributeDamage\|Attribute Damage]]. | Improvised weapons    |
| 3    | Severe   | Fractures, stab wounds, deep lacerations.                                           | Injury Effect.                                        | Purpose built weapons |
| 4    | Critical | Severed tendons, punctured organs.                                                  | Disables the location. Can be Letahal.                | Two handed weapons    |
| 5    | Brutal   | Decapitation, hitting the ground at terminal velocity, gettin’ chomped by a dragon. | Lethal always.                                        | Siege engines         |

## Tracking Injuries
In the [[character_sheet|Character Sheet]], each Hit Location has a tracker with the Levels of Injury that location can receive.

When a PC receives an Injury in a Hit Location, it fills the box corresponding to the level of that injury.

If an injury of that level was already marked, the injury escalates to be one level higher. This can happen two times. If the injury escalates a third time, it simply re-applies its Injury effect.

![[exPlay_receivingInjuries#`= this.file.aliases[0]`]]

## Injury Effects
When a character recives an Injuries of Severe level or above (3+), they must pass an [[skill_endure|ENDURE]] [[coreMec_rollResolution|Roll]] or also recive the corresponding Injury Effect.

### Serious Injury: Attribute Damage
Hit Locations have an associated [[coreMec_attributes|Attribute]] ([[attr_strength|STRENGTH]] or [[attr_agility|AGILITY]]).

Each time a new Injury above Minor Level is marked, the associated [[coreMec_attributes|Attribute]] recives [[coreMec_attributeDamage|Attribute Damage]].

### Severe Injury: Effect vs. Hit Location

| Location | Effect         | Description                                  |
| -------- | -------------- | -------------------------------------------- |
| `HEAD`   | Knock out      | Become [[coreMec_fallUnconscious\|Unconscious]].         |
| `ARM`    | Disarm         | Drop whatever is in this hand.               |
| `LEG`    | Knock prone    | Fall to the ground                           |
| `TORSO`  | Crippling pain | As for leg if standing, as for head if prone |
### Critical Injury: Disabling Locations
A critical injury always disables the location it hits.
#### Disabled Limbs
When arms or legs recive a Critical Injury, they get Disabled:
- That limb cannot perform any action.
- If an arm, that hand cannot hold anything or be used to attack.
- If a leg, it limits movement to [[coreMec_combat_distance|Half a Chain (within that zone)]].
- The PC cannot climb (even with a single disabled limb).

#### Disabled Head or Torso
The injury is considered as a Lethal Injury to that location.

## Lethal Injuries
On every turn after sustaining a Lethal Injury, the PC must succeed on an [[skill_endure|ENDURE]] [[coreMec_rollResolution|Roll]] or die.

### Stabilizing a Lethal Injury
A stabilized Lethal Injury no longer needs [[skill_endure|ENDURE]] [[coreMec_rollResolution|Rolls]] each [[coreMec_combat_turn|Combat Turn]], but still remains until [[healing|Healed]] regularly.

While [[coreMec_fallUnconscious|Unconscious]], [[skill_endure|ENDURE]] [[coreMec_rollResolution|Rolls]] to avoid [[coreMec_death|Death]] from a Lethal Injury are at `EASY` [[coreMec_difficulty|Difficulty]].
> Remember that a PC with lots of Attribute Damage or a Lethal injury can choose to fall unconscious.

To stabilize a Lethal Injury:
- A different PC must succeed on a [[skill_surgery|SURGERY]] [[coreMec_rollResolution|Roll]].
- [[item_bandages|Bandages]] must be used as part of the action.
- Any number of [[skill_surgery|SURGERY]] rolls can be attempted, but:
	- A single [[skill_surgery|SURGERY]] [[coreMec_rollResolution|Roll]] can be made per [[coreMec_combat_turn|Combat Turn]].
	- Between every [[skill_surgery|SURGERY]] [[coreMec_rollResolution|Roll]] and the next one, the wounded PC must have passed one [[skill_endure|ENDURE]] [[coreMec_rollResolution|Roll]] in their [[coreMec_combat_turn|Combat Turn]].

## Brutal Injuries
When a PC takes a Brutal Injury, the hit location is destroyed.
> Decapitations, crushed skulls, disembowelment, caved chests, amputations, manglements...

### Head or Torso
Automatic [[coreMec_death|Death]].

### Limb
Destroyed limb. Counts as a Lethal Injury.

#### Attribute Effect
Reduce the maximum for the relevant [[coreMec_attributes|Attribute]]. If it gets reduced to less than two points, the PC is crippled, and cannot make [[coreMec_rollResolution|Rolls]] of the associated [[coreMec_skills|Skills]] unless they have at least one point in them. It is still possible to [[coreMec_skillTraining|Train]] to be able to use them.

Any previous Injuries on that limb still need to heal to recover the pertinent [[coreMec_attributeDamage|Attribute Damage]].

#### Limb as Hit Location
Scratch that limb from the sheet. Any further attack that targets the limb, targets the `TORSO` instead.
