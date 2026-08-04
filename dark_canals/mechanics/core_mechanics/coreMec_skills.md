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
- They can be increased by [[coreMec_skillTraining|Training]].
- Skills are categorized in three groups corresponding to their associated [[coreMec_attributes|Attribute]].

Skills work in combination with [[coreMec_attributes|Attributes]]:
- The Dice pool of any given [[coreMec_rollResolution|Roll]] is composed by a number of dice equal to the ratings of a Skill and an [[coreMec_attributes|Attribute]].
- Usually, the Skill uses the rating of its category of [[coreMec_attributes|Attribute]]. However, this is not mandatory.
- If the Skill rating is 0, the roll is made with the [[coreMec_attributes|Attribute]] rating alone.
- When doing [[coreMec_opposedRolls|Opposed Rolls]], the selected [[coreMec_attributes|Attributes]] and [[coreMec_skills|Skills]] for the two opposing parties can be different.

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
| [[skill_physique\|PHYSIQUE]]       | [[attr_strength\|STRENGTH]] |
| [[skill_fight\|FIGHT]]             | [[attr_strength\|STRENGTH]] |
| [[skill_endure\|ENDURE]]           | [[attr_strength\|STRENGTH]] |
| [[skill_ballistics\|BALLISTICS]]   | [[attr_agility\|AGILITY]]   |
| [[skill_mobility\|MOBILITY]]       | [[attr_agility\|AGILITY]]   |
| [[skill_techne\|TECHNE]]           | [[attr_agility\|AGILITY]]   |
| [[skill_surgery\|SURGERY]]         | [[attr_wits\|WITS]]         |
| [[skill_observation\|OBSERVATION]] | [[attr_wits\|WITS]]         |
| [[skill_reason\|REASON]]           | [[attr_wits\|WITS]]         |
| [[skill_appeal\|APPEAL]]           | [[attr_empathy\|EMPATHY]]   |
| [[skill_insight\|INSIGHT]]         | [[attr_empathy\|EMPATHY]]   |
| [[skill_connections\|CONNECTIONS]] | [[attr_empathy\|EMPATHY]]   |

## Tracking Skills in the [[character_sheet|Character Sheet]]
- Mark skill ratings by writing their numbers sequentially, in the boxes.
- Blank out boxes from the right when [[coreMec_skillTraining|Training]] a different skill.