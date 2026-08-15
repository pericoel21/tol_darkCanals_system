---
tags:
  - core
  - mechanic
aliases:
  - Pushing the Roll
  - Push the Roll
  - Push
  - Pushing
connections:
description: Spending Stamina or Resolve allows a character to ignore Attribute Damage on a roll.
---
# `= this.file.aliases[0]`
> `= this.description`.

In order to push a roll, a PC must spend:
- One [[stat_resolve|Resolve]] for [[attribute_wits|WITS]] or [[attribute_empathy|EMPATHY]] [[mechanic_attributeDamage|Attribute Damage]].
- One [[stat_stamina|Stamina]] for [[attribute_strength|STRENGTH]] or [[attribute_agility|AGILITY]] [[mechanic_attributeDamage|Attribute Damage]].

A PC can push the roll before or after rolling and determining the [[mechanic_rollResolution|Outcome of the Roll]]:
- Before rolling:
	1. Ignore [[mechanic_attributeDamage|Attribute Damage]].
	2. Roll with the whole [[mechanic_attributes|Attribute]] rating.
	3. Calculate the [[mechanic_rollResolution|Outcome of the Roll]].
- After rolling: 
	1. Keep the already rolled dice.
	2. Roll additional dice. You want to have the number of dice rolled be as if your [[mechanic_attributes|Attribute]] was untouched by [[mechanic_attributeDamage|Attribute Damage]].
	3. Re-calculate the [[mechanic_rollResolution|Outcome of the Roll]].

If the dice pool of a roll ([[mechanic_skills|Skill]] + [[mechanic_attributes|Attribute]]) is under two die (one or less), the roll cannot be made without pushing.