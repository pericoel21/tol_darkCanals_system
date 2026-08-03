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

1. Adjudicate if the roll is relevant, and the [[coreMec_difficulty|Difficulty]].
	- A roll might be `Impossible` Difficulty, or auto-succeed because it is easier than `Very Easy`.
	- Routine actions might not need to be rolled.
	- If someone is [[coreMec_helping|helping]] with the action, the [[coreMec_difficulty|Difficulty]] will probably go down. 

2. Select the PC's current, relevant [[coreMec_attributes|Attribute]] and [[coreMec_skills|Skill]] ratings.
	- If the [[coreMec_skills|Skill]] rating is 0, simply count the [[coreMec_attributes|Attribute]] rating.
	- If the combined rating is under 2 (1 or less) due to [[coreMec_attributeDamage|Attribute Damage]], the roll cannot be made unless [[coreMec_pushingRolls|the Roll is Pushed]].

3. Determine if the roll has a [[coreMec_modifier|Modifier]].
	- [[coreMec_modifier|The Modifier]] comes from one of the PC's [[coreMec_profficiencies|Proficiencies]].
	- [[coreMec_modifier|Modifiers]] never stack up, the maximum is one.
	- A [[coreMec_modifier|Modifier]] grants an extra die.

4. Consider [[coreMec_pushingRolls|Pushing the Roll]] to ignore [[coreMec_attributeDamage|Attribute Damage]].
	- Spend one [[coreMec_resolve|Resolve]] (for [[wits_attr|WITS]] or [[empathy_attr|EMPATHY]]).
	- Spend one [[coreMec_stamina|Stamina]] (for [[strength_attr|STRENGTH]] or [[agility_attr|AGILITY]]).
	
5. Roll a number of D6 equal to [[coreMec_attributes|Attribute]] rating + [[coreMec_skills|Skill]] rating + [[coreMec_modifier|Modifier]] (if any).

6. Select the highest two dice results. Those are the `Success Dice`.

7. Compare them individually to the [[coreMec_difficulty|Difficulty]] requirements.
	- Usually, success happens when both are 5s or higher.
	- When an NPC opposes a PC roll, that NPC's dice pool is used as a [[coreMec_difficulty|Difficulty]] gauge.
	- Opposed rolls can still be used, especially when PCs are confronting each other. This, however, is not recommended.

8. Determine success or failure.
	- The target (set by [[coreMec_difficulty|Difficulty]]) is not the sum of the dice. It is a set of two dice which are compared individually to the two highest dice rolled (the `Success Dice`).
	- Both `Success Dice` must be equal or higher to those the [[coreMec_difficulty|Difficulty]] demands for the roll to succeed.

9. Calculate [[coreMec_degreesOfSuccess| the Degrees of Success]], if needed.
	- In some cases, a roll with 0 Degrees of Success (exactly meeting the Difficulty) is considered as a success with a consequence.

10. Consider [[coreMec_pushingRolls|Pushing the Roll]] to ignore [[coreMec_attributeDamage|Attribute Damage]].
	- Roll the remaining dice and add them to the pool.
	- Then, determine success or failure and [[coreMec_degreesOfSuccess|Degrees of Success]].

11. Final considerations:
	- There's no rolling for the same thing again. A failure means the whole approach is wrong. Try something different, if this failed.
	- If you succeeded, you succeeded all the way. No "half-way there".
	- At this point, a successful [[coreMec_helping|Helping Action]] can transform a failed roll with -1 [[coreMec_degreesOfSuccess|Degrees of Success]] into a success (under very specific situations). 

