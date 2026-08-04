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
- One [[stat_resolve|Resolve]] for [[attr_wits|WITS]] or [[attr_empathy|EMPATHY]] [[coreMec_attributeDamage|Attribute Damage]].
- One [[stat_stamina|Stamina]] for [[attr_strength|STRENGTH]] or [[attr_agility|AGILITY]] [[coreMec_attributeDamage|Attribute Damage]].

A PC can push the roll before or after rolling and determining the [[coreMec_rollResolution|Outcome of the Roll]]:
- Before rolling:
	1. Ignore [[coreMec_attributeDamage|Attribute Damage]].
	2. Roll with the whole [[coreMec_attributes|Attribute]] rating.
	3. Calculate the [[coreMec_rollResolution|Outcome of the Roll]].
- After rolling: 
	1. Keep the already rolled dice.
	2. Roll additional dice. You want to have the number of dice rolled be as if your [[coreMec_attributes|Attribute]] was untouched by [[coreMec_attributeDamage|Attribute Damage]].
	3. Re-calculate the [[coreMec_rollResolution|Outcome of the Roll]].

If the dice pool of a roll ([[coreMec_skills|Skill]] + [[coreMec_attributes|Attribute]]) is under two die (one or less), the roll cannot be made without pushing.