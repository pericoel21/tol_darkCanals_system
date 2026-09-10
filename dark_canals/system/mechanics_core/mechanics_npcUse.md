---
tags:
  - mechanic
  - core
aliases:
  - Using NPCs
connections:
  - "[[mechanic_npcCreation|NPC Creation]]"
description: Whenever a PC woud have to roll for something, an NPC spends resources, instead
---
# `= this.file.aliases[0]`
> `= this.description`.

## Spending Stamina
NPCs spend one [[stat_stamina|Stamina]] instead of rolling for:
- [[mechanic_injury|Injury effect]].
- [[mechanic_fallUnconscious|Falling Unconscious]].
- Avoid dying from a `LETHAL` [[mechanic_injury|Injury]].
- Ignoring [[mechanic_attributeDamage|Attribute Damage]] (NPCs always do it)

### Attribute Damage
NPCs always choose to spend [[stat_stamina|Stamina]] to ignore [[mechanic_attributeDamage|Attribute Damage]]:
- Unless GM sees value in depicting a weakening NPC.
- Until they run out of [[stat_stamina|Stamina]]

When their [[stat_stamina|Stamina]] is 0, that's the point the NPC would flee or yield.

## Morale & Goals
The combat should end as soon as the winner is obvious.
- At the start of the combat, NPCs flee or yield if they think they'll loose, or if they are not combatants.
- The combatant NPC's goal is to slay or incapacitate the enemy before running out of [[stat_stamina|Stamina]] or [[stat_resolve|Resolve]].
- If the enemy stands when their [[stat_stamina|Stamina]] or [[stat_resolve|Resolve]], they will attempt to flee or yield.
- Fleeing can be useful to recover and attack again.

## Disposition
- NPC disposition can be rolled with the [[mechanic_randomEncounters]].
- No need to roll disposition if GM already knows.
- Not all NPCs aggro, or have the whole range of dispositions.

## Magic
- An NPC only casts within the [[mechanic_profficiencies|Proficiencies]] they have (for [[magic_forms|Forms]] and [[magic_techniques|Magic Techniques]]).
- If the [[magic_spellLevel|Spell Level]] is under their relevant [[mechanic_skills|Skill]]:
	- It always succeeds (can be [[magic_spellResistance|resisted]]).
	- Costs 1 [[stat_resolve|Resolve]]
- Higher level spells might be attempted and rolled by the GM.
