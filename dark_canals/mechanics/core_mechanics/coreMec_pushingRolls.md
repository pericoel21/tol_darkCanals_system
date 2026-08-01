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
- One [[dark_canals/mechanics/core_mechanics/coreMec_resolve|Resolve]] for [[wits_attr|WITS]] or [[empathy_attr|EMPATHY]] [[dark_canals/mechanics/core_mechanics/coreMec_attributeDamage|Attribute Damage]].
- One [[dark_canals/mechanics/core_mechanics/coreMec_stamina|Stamina]] for [[strength_attr|STRENGTH]] or [[agility_attr|AGILITY]] [[dark_canals/mechanics/core_mechanics/coreMec_attributeDamage|Attribute Damage]].

A PC can push the roll before or after rolling and determining the [[dark_canals/mechanics/core_mechanics/coreMec_rollResolution|Outcome of the Roll]]:
- Before rolling:
	1. Ignore [[dark_canals/mechanics/core_mechanics/coreMec_attributeDamage|Attribute Damage]].
	2. Roll with the whole [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attribute]] rating.
	3. Calculate the [[dark_canals/mechanics/core_mechanics/coreMec_rollResolution|Outcome of the Roll]].
- After rolling: 
	1. Keep the already rolled dice.
	2. Roll additional dice. You want to have the number of dice rolled be as if your [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attribute]] was untouched by [[dark_canals/mechanics/core_mechanics/coreMec_attributeDamage|Attribute Damage]].
	3. Re-calculate the [[dark_canals/mechanics/core_mechanics/coreMec_rollResolution|Outcome of the Roll]].

If the dice pool of a roll ([[dark_canals/mechanics/core_mechanics/coreMec_skills|Skill]] + [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attribute]]) is under two die (one or less), the roll cannot be made without pushing.