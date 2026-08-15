---
tags:
  - core
  - mechanic
  - stat
aliases:
  - Skills
  - Skill
connections:
description: Knowledge and abilities a character holds
---
# `= this.file.aliases[0]`
> `= this.description`.

- Skills determine how effectively a Character can perform certain actions.
- They can be increased by [[mechanic_skillTraining|Training]].
- Skills are categorized in three groups corresponding to their associated [[mechanic_attributes|Attribute]].

Skills work in combination with [[mechanic_attributes|Attributes]]:
- The Dice pool of any given [[mechanic_rollResolution|Roll]] is composed by a number of dice equal to the ratings of a Skill and an [[mechanic_attributes|Attribute]].
- Usually, the Skill uses the rating of its category of [[mechanic_attributes|Attribute]]. However, this is not mandatory.
- If the Skill rating is 0, the roll is made with the [[mechanic_attributes|Attribute]] rating alone.
- When doing [[mechanic_opposedRolls|Opposed Rolls]], the selected [[mechanic_attributes|Attributes]] and [[mechanic_skills|Skills]] for the two opposing parties can be different.

> It shouldn't be needed to use the actual name of the skill during play, see [[phi_usingSkillsReification]]

### Skill Ratings

| Rating | Meaning     |
| ------ | ----------- |
| 5      | Elite       |
| 4      | Veteran     |
| 3      | Experienced |
| 2      | Novice      |
| 1      | Initiate    |
| 0      | Untrained   |

## List of Skills

| Name                               | Attribute                   |
| ---------------------------------- | --------------------------- |
| [[skill_physique\|PHYSIQUE]]       | [[attribute_strength\|STRENGTH]] |
| [[skill_fight\|FIGHT]]             | [[attribute_strength\|STRENGTH]] |
| [[skill_endure\|ENDURE]]           | [[attribute_strength\|STRENGTH]] |
| [[skill_ballistics\|BALLISTICS]]   | [[attribute_agility\|AGILITY]]   |
| [[skill_mobility\|MOBILITY]]       | [[attribute_agility\|AGILITY]]   |
| [[skill_techne\|TECHNE]]           | [[attribute_agility\|AGILITY]]   |
| [[skill_surgery\|SURGERY]]         | [[attribute_wits\|WITS]]         |
| [[skill_observation\|OBSERVATION]] | [[attribute_wits\|WITS]]         |
| [[skill_reason\|REASON]]           | [[attribute_wits\|WITS]]         |
| [[skill_appeal\|APPEAL]]           | [[attribute_empathy\|EMPATHY]]   |
| [[skill_insight\|INSIGHT]]         | [[attribute_empathy\|EMPATHY]]   |
| [[skill_connections\|CONNECTIONS]] | [[attribute_empathy\|EMPATHY]]   |

## Tracking Skills in the [[character_sheet|Character Sheet]]
- Mark skill ratings by writing their numbers sequentially, in the boxes.
- Blank out boxes from the right when [[mechanic_skillTraining|Training]] a different skill.