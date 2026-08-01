---
tags:
  - core
  - mechanic
aliases:
  - The Core Resolution Mechanic
  - Roll
  - Rolls
connections:
description: Core process of roll resolution
---
# `= this.file.aliases[0]`
> `= this.description`.

1. Adjudicate if the roll is relevant, and the [[dark_canals/mechanics/core_mechanics/coreMec_difficulty|Difficulty]].
	- A roll might be `Impossible` Difficulty, or auto-succeed because it is easier than `Very Easy`.
	- Routine actions might not need to be rolled.
	- If someone is [[dark_canals/mechanics/core_mechanics/coreMec_helping|helping]] with the action, the [[dark_canals/mechanics/core_mechanics/coreMec_difficulty|Difficulty]] will probably go down. 

2. Select the PC's current, relevant [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attribute]] and [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skill]] ratings.
	- If the [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skill]] rating is 0, simply count the [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attribute]] rating.
	- If the combined rating is under 2 (1 or less) due to [[dark_canals/mechanics/core_mechanics/coreMec_attributeDamage|Attribute Damage]], the roll cannot be made unless [[dark_canals/mechanics/core_mechanics/coreMec_pushingRolls|the Roll is Pushed]].

3. Determine if the roll has a [[dark_canals/mechanics/core_mechanics/coreMec_modifier|Modifier]].
	- [[dark_canals/mechanics/core_mechanics/coreMec_modifier|The Modifier]] comes from one of the PC's [[dark_canals/mechanics/core_mechanics/coreMec_profficiencies|Proficiencies]].
	- [[dark_canals/mechanics/core_mechanics/coreMec_modifier|Modifiers]] never stack up, the maximum is one.
	- A [[dark_canals/mechanics/core_mechanics/coreMec_modifier|Modifier]] grants an extra die.

4. Consider [[dark_canals/mechanics/core_mechanics/coreMec_pushingRolls|Pushing the Roll]] to ignore [[dark_canals/mechanics/core_mechanics/coreMec_attributeDamage|Attribute Damage]].
	- Spend one [[dark_canals/mechanics/core_mechanics/coreMec_resolve|Resolve]] (for [[wits_attr|WITS]] or [[empathy_attr|EMPATHY]]).
	- Spend one [[dark_canals/mechanics/core_mechanics/coreMec_stamina|Stamina]] (for [[strength_attr|STRENGTH]] or [[agility_attr|AGILITY]]).
	
5. Roll a number of D6 equal to [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attribute]] rating + [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skill]] rating + [[dark_canals/mechanics/core_mechanics/coreMec_modifier|Modifier]] (if any).

6. Select the highest two dice results. Those are the `Success Dice`.

7. Compare them individually to the [[dark_canals/mechanics/core_mechanics/coreMec_difficulty|Difficulty]] requirements.
	- Usually, success happens when both are 5s or higher.
	- When an NPC opposes a PC roll, that NPC's dice pool is used as a [[dark_canals/mechanics/core_mechanics/coreMec_difficulty|Difficulty]] gauge.
	- Opposed rolls can still be used, especially when PCs are confronting each other. This, however, is not recommended.

8. Determine success or failure.
	- The target (set by [[dark_canals/mechanics/core_mechanics/coreMec_difficulty|Difficulty]]) is not the sum of the dice. It is a set of two dice which are compared individually to the two highest dice rolled (the `Success Dice`).
	- Both `Success Dice` must be equal or higher to those the [[dark_canals/mechanics/core_mechanics/coreMec_difficulty|Difficulty]] demands for the roll to succeed.

9. Calculate [[dark_canals/mechanics/core_mechanics/coreMec_degreesOfSuccess| the Degrees of Success]], if needed.
	- In some cases, a roll with 0 Degrees of Success (exactly meeting the Difficulty) is considered as a success with a consequence.

10. Consider [[dark_canals/mechanics/core_mechanics/coreMec_pushingRolls|Pushing the Roll]] to ignore [[dark_canals/mechanics/core_mechanics/coreMec_attributeDamage|Attribute Damage]].
	- Roll the remaining dice and add them to the pool.
	- Then, determine success or failure and [[dark_canals/mechanics/core_mechanics/coreMec_degreesOfSuccess|Degrees of Success]].

11. Final considerations:
	- There's no rolling for the same thing again. A failure means the whole approach is wrong. Try something different, if this failed.
	- If you succeeded, you succeeded all the way. No "half-way there".
	- At this point, a successful [[dark_canals/mechanics/core_mechanics/coreMec_helping|Helping Action]] can transform a failed roll with -1 [[dark_canals/mechanics/core_mechanics/coreMec_degreesOfSuccess|Degrees of Success]] into a success (under very specific situations). 

