---
tags:
  - magic
  - core
  - mechanic
aliases:
  - Casting Magic
  - Casting
connections:
description: Casting requires a full turn, a visual description, and the use of one form and one technique
---
# `= this.file.aliases[0]`
> `= this.description`.

## Step by Step
1. Casting consumes a [[combat_turn|full turn]], including the movement.

2. The player describes how the PC sees the spell through [[magic_lens|The Lens]].
	- Therefore, spells must ve "visual".

3. Select at least one [[magic_forms|Form]] and at least one [[magic_techniques|Technique]].
	- You might select [[magic_forms|Forms]] or [[magic_techniques|Techniques]] outside the caster's [[mechanic_profficiencies|Proficiencies]]. It adds difficulty (step 7).
	- A spell with two [[magic_forms|Forms]] or [[magic_techniques|Techniques]] that the caster is not proficient with, automatically fails.

4. Select a subject.
	- Willing subjects may resist (step 8).
	- [[magic_lattices|Lattices]] are immune.

5. Calculate the [[magic_spellLevel|Spell Level]].
	- The spell level cannot be higher than the caster's [[mechanic_skills|Skill]] score.

6. Determine the [[magic_spellDifficulty|Spell Difficulty]].
	- Compare the [[magic_spellLevel|Level of the Spell]] that the Player wants to use against the one calculated by the book.

6. [[mechanic_rollResolution|Roll]]:
	- [[mechanic_attributes|Attribute]] used:
		- [[skill_reason|REASON]] for [[wizards]].
		- [[skill_insight|INSIGHT]] for [[chosen]].
	- Substitute [[stress die]] equal to the [[magic_spellLevel]].
	- If using one [[magic_forms|Form]] or [[magic_techniques|Technique]] outside the caster's [[mechanic_profficiencies|Proficiencies]], roll only with the corresponding [[mechanic_attributes|Attribute]].
	- If using more than one [[magic_forms|Form]] or [[magic_techniques|Technique]] outside the caster's [[mechanic_profficiencies|Proficiencies]], the spell fails.

8. A willing subject may resist the spell.

9. If the roll meets the [[mechanic_difficulty|Difficulty]], the spell effect resolves.

10. Results of 1 in [[stress die|Stress Dice]] cause [[magic_mishaps|Magic Mishaps]].
	- [[stat_resolve|Resolve]] can cancel 1s ina a 1:1 basis.
	- A result of five 1s means death.

11. [[magic_concentration|Concentrate]] on the spell every subsequent [[combat_turn|Turn]], if the spell has an ongoing effect.

## Requirements
### Spell Level
The [[magic_spellLevel|Level of the Spell]] cannot be higher than the caster's relevant [[mechanic_skills|Skill]] (note: not the whole dice pool, but only the [[mechanic_skills|Skill]] used as part of it).

### Targeting
- A single spell targets a single subject.
- All effects of the spell are applied to the same part of the same subject.
- Several effects can be applied all at once.
- No antithetical effects can be applied simultaneously.

### Subject
- Anything visible can be targeted.
- Not seeing is what's relevant, not the distance.
- The less clearly visible something is, the `HARDER` [[mechanic_difficulty|Difficulty]] is to cast a spell.
- Exception to visibility requirement: [[magic_entanglement|Entanglement]].

#### Subject vs. Target
- Subject is where the magic is created or applied.
- Target is a possible location or character that may be affected by already created magic.
- Subjects might resist being subjected to magic.
- Targets might avoid magic as if avoiding any other physical effect.