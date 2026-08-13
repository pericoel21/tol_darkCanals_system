---
tags:
  - core
  - mechanic
aliases:
  - Attribute Damage
connections:
description: Injury or conditions can cause attributes to temporarily be lower than the character's maximum
---
# `= this.file.aliases[0]`
> `= this.description`.

It can be ignored by [[coreMec_pushingRolls|Pushing the Roll]].

Which [[coreMec_attributes|Attribute]] gets Attribute Damage is always indicated in the [[coreMec_injury|Injury]] or [[coreMec_conditions|Condition]].

Attribute damage can be reversed, so it gets marked by crossing it off (to differentiate it from the blanked cells that define the base [[coreMec_attributes|Attribute]] score).

When a PC's Attribute Damage exceeds their [[coreMec_attributes|Attribute]] score, they might choose to [[coreMec_fallUnconscious|Fall Unconscious]].

## Effects
### Training
[[coreMec_skillTraining|Skill Training]] cannot be perfromed with a [[coreMec_skills|Skill]] under an [[coreMec_attributes|Attribute]] that is damaged.

### Attribute Depletion
If a PC suffers  Attribute Damage in excess of the [[coreMec_attributes|Attribute's]]’s rating, the [[coreMec_rollResolution|Rolls]] for that [[coreMec_attributes|Attribute]] can no longer be [[coreMec_pushingRolls|Pushed]].

### Effect due to Condition
[[coreMec_conditions|Condition]] cause specific effects if they damage [[coreMec_attributes|Attributes]] by an amount equal to the maximum of that [[coreMec_attributes|Attribute]].

Attribute Damage caused by [[coreMec_injury|Injuries]] do not affect the calculation.

| Attribute                   | Effect                      |
| --------------------------- | --------------------------- |
| [[attr_strength\|STRENGTH]] | Death                       |
| [[attr_agility\|AGILITY]]   | Death                       |
| [[attr_empathy\|EMPATHY]]   | Breakdown (purely roleplay) |
| [[attr_wits\|WITS]]         | Pass out                    |
