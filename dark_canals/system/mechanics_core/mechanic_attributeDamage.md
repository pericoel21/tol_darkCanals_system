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

It can be ignored by [[mechanic_pushingRolls|Pushing the Roll]].

Which [[mechanic_attributes|Attribute]] gets Attribute Damage is always indicated in the [[mechanic_injury|Injury]] or [[mechanic_conditions|Condition]].

Attribute damage can be reversed, so it gets marked by crossing it off (to differentiate it from the blanked cells that define the base [[mechanic_attributes|Attribute]] score).

When a PC's Attribute Damage exceeds their [[mechanic_attributes|Attribute]] score, they might choose to [[mechanic_fallUnconscious|Fall Unconscious]].

## Effects
### Training
[[mechanic_skillTraining|Skill Training]] cannot be perfromed with a [[mechanic_skills|Skill]] under an [[mechanic_attributes|Attribute]] that is damaged.

### Attribute Depletion
If a PC suffers  Attribute Damage in excess of the [[mechanic_attributes|Attribute's]]’s rating, the [[mechanic_rollResolution|Rolls]] for that [[mechanic_attributes|Attribute]] can no longer be [[mechanic_pushingRolls|Pushed]].

### Effect due to Condition
[[mechanic_conditions|Condition]] cause specific effects if they damage [[mechanic_attributes|Attributes]] by an amount equal to the maximum of that [[mechanic_attributes|Attribute]].

Attribute Damage caused by [[mechanic_injury|Injuries]] do not affect the calculation.

| Attribute                   | Effect                      |
| --------------------------- | --------------------------- |
| [[attribute_strength\|STRENGTH]] | Death                       |
| [[attribute_agility\|AGILITY]]   | Death                       |
| [[attribute_empathy\|EMPATHY]]   | Breakdown (purely roleplay) |
| [[attribute_wits\|WITS]]         | Pass out                    |
