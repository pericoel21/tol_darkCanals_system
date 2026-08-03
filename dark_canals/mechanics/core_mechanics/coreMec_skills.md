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
- They can be increased by [[training|Training]].
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
| [[skills/skill_physique\|PHYSIQUE]]       | [[strength_attr\|STRENGTH]] |
| [[skills/skill_fight\|FIGHT]]             | [[strength_attr\|STRENGTH]] |
| [[skills/skill_endure\|ENDURE]]           | [[strength_attr\|STRENGTH]] |
| [[skills/skill_ballistics\|BALLISTICS]]   | [[agility_attr\|AGILITY]]   |
| [[skills/skill_mobility\|MOBILITY]]       | [[agility_attr\|AGILITY]]   |
| [[skills/skill_techne\|TECHNE]]           | [[agility_attr\|AGILITY]]   |
| [[skills/skill_surgery\|SURGERY]]         | [[wits_attr\|WITS]]         |
| [[skills/skill_observation\|OBSERVATION]] | [[wits_attr\|WITS]]         |
| [[skills/skill_reason\|REASON]]           | [[wits_attr\|WITS]]         |
| [[skills/skill_appeal\|APPEAL]]           | [[empathy_attr\|EMPATHY]]   |
| [[skills/skill_insight\|INSIGHT]]         | [[empathy_attr\|EMPATHY]]   |
| [[skills/skill_connections\|CONNECTIONS]] | [[empathy_attr\|EMPATHY]]   |

