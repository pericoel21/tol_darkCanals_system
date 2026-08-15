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

1. Adjudicate if the roll is relevant, and the [[mechanic_difficulty|Difficulty]].
	- A roll might be `Impossible` Difficulty, or auto-succeed because it is easier than `Very Easy`.
	- Routine actions might not need to be rolled.
	- If someone is [[mechanic_helping|helping]] with the action, the [[mechanic_difficulty|Difficulty]] will probably go down. 

2. Select the PC's current, relevant [[mechanic_attributes|Attribute]] and [[mechanic_skills|Skill]] ratings.
	- If the [[mechanic_skills|Skill]] rating is 0, simply count the [[mechanic_attributes|Attribute]] rating.
	- If the combined rating is under 2 (1 or less) due to [[mechanic_attributeDamage|Attribute Damage]], the roll cannot be made unless [[mechanic_pushingRolls|the Roll is Pushed]].

3. Determine if the roll has a [[mechanic_modifier|Modifier]].
	- [[mechanic_modifier|The Modifier]] comes from one of the PC's [[mechanic_profficiencies|Proficiencies]].
	- [[mechanic_modifier|Modifiers]] never stack up, the maximum is one.
	- A [[mechanic_modifier|Modifier]] grants an extra die.

4. Consider [[mechanic_pushingRolls|Pushing the Roll]] to ignore [[mechanic_attributeDamage|Attribute Damage]].
	- Spend one [[stat_resolve|Resolve]] (for [[attribute_wits|WITS]] or [[attribute_empathy|EMPATHY]]).
	- Spend one [[stat_stamina|Stamina]] (for [[attribute_strength|STRENGTH]] or [[attribute_agility|AGILITY]]).
	
5. Roll a number of D6 equal to [[mechanic_attributes|Attribute]] rating + [[mechanic_skills|Skill]] rating + [[mechanic_modifier|Modifier]] (if any).

6. Select the highest two dice results. Those are the `Success Dice`.

7. Compare them individually to the [[mechanic_difficulty|Difficulty]] requirements.
	- Usually, success happens when both are 5s or higher.
	- When an NPC opposes a PC roll, that NPC's dice pool is used as a [[mechanic_difficulty|Difficulty]] gauge.
	- Opposed rolls can still be used, especially when PCs are confronting each other. This, however, is not recommended.

8. Determine success or failure.
	- The target (set by [[mechanic_difficulty|Difficulty]]) is not the sum of the dice. It is a set of two dice which are compared individually to the two highest dice rolled (the `Success Dice`).
	- Both `Success Dice` must be equal or higher to those the [[mechanic_difficulty|Difficulty]] demands for the roll to succeed.

9. Calculate [[mechanic_degreesOfSuccess| the Degrees of Success]], if needed.
	- In some cases, a roll with 0 Degrees of Success (exactly meeting the Difficulty) is considered as a success with a consequence.

10. Consider [[mechanic_pushingRolls|Pushing the Roll]] to ignore [[mechanic_attributeDamage|Attribute Damage]].
	- Roll the remaining dice and add them to the pool.
	- Then, determine success or failure and [[mechanic_degreesOfSuccess|Degrees of Success]].

11. Final considerations:
	- There's no rolling for the same thing again. A failure means the whole approach is wrong. Try something different, if this failed.
	- If you succeeded, you succeeded all the way. No "half-way there".
	- At this point, a successful [[mechanic_helping|Helping Action]] can transform a failed roll with -1 [[mechanic_degreesOfSuccess|Degrees of Success]] into a success (under very specific situations). 

