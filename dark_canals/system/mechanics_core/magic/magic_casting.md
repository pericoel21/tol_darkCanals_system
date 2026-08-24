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
	 - Parse the description to select spell effects and calculate the [[spell level]].
	 - The spell level cannot be higher than the caster's [[mechanic_skills|Skill]] score.

3. Select at least one [[magic_forms|Form]] and at least one [[magic_techniques|Technique]].
	- You might select [[magic_forms|Forms]] or [[magic_techniques|Techniques]] outside the caster's [[mechanic_profficiencies|Proficiencies]]. It adds difficulty (step 5).

4. Select a subject.
	- Willing subjects may resist (step 6).
	- [[magic_lattices|Lattices]] are immune.

5. [[mechanic_rollResolution|Roll]]:
	- [[mechanic_attributes|Attribute]] used:
		- [[skill_reason|REASON]] for [[wizards]].
		- [[skill_insight|INSIGHT]] for [[chosen]].
	- Substitute [[stress die]] equal to the [[spell level]].
	- If using one [[magic_forms|Form]] or [[magic_techniques|Technique]] outside the caster's [[mechanic_profficiencies|Proficiencies]], roll only with the corresponding [[mechanic_attributes|Attribute]].
	- If using more than one [[magic_forms|Form]] or [[magic_techniques|Technique]] outside the caster's [[mechanic_profficiencies|Proficiencies]], the spell fails.

6. A willing subject may resist the spell.

7. If the roll meets the [[mechanic_difficulty|Difficulty]], the spell effect resolves.

## Requirements
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