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

Skills determine how effectively a Character can perform certain actions. They can be increased by [[training|Training]].

Skills are categorized by their associated [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attribute]].

Skills work in combination with [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attributes]]:
- The Dice pool of any given [[dark_canals/mechanics/core_mechanics/coreMec_rollResolution|Roll]] is composed by a number of dice equal to the ratings of a Skill and an [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attribute]].
- Usually, the Skill uses the rating of its category of [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attribute]]. However, this is not mandatory.
- If the Skill rating is 0, the roll is made with the [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attribute]] rating alone.
- When doing [[dark_canals/mechanics/core_mechanics/coreMec_opposedRolls|Opposed Rolls]], the selected [[dark_canals/mechanics/core_mechanics/coreMec_attributes|Attributes]] and [[dark_canals/mechanics/core_mechanics/coreMec_skills|Skills]] for the two opposing parties can be different.

> It shouldn't be needed to use the actual name of the skill during play, see [[dark_canals/philosophy/phi_usingSkillsReification|phi_usingSkillsReification]]

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
| [[dark_canals/mechanics/core_mechanics/skills/skill_physique\|PHYSIQUE]]       | [[strength_attr\|STRENGTH]] |
| [[dark_canals/mechanics/core_mechanics/skills/skill_fight\|FIGHT]]             | [[strength_attr\|STRENGTH]] |
| [[dark_canals/mechanics/core_mechanics/skills/skill_endure\|ENDURE]]           | [[strength_attr\|STRENGTH]] |
| [[dark_canals/mechanics/core_mechanics/skills/skill_ballistics\|BALLISTICS]]   | [[agility_attr\|AGILITY]]   |
| [[dark_canals/mechanics/core_mechanics/skills/skill_mobility\|MOBILITY]]       | [[agility_attr\|AGILITY]]   |
| [[dark_canals/mechanics/core_mechanics/skills/techne_skill\|TECHNE]]           | [[agility_attr\|AGILITY]]   |
| [[dark_canals/mechanics/core_mechanics/skills/surgery_skill\|SURGERY]]         | [[wits_attr\|WITS]]         |
| [[dark_canals/mechanics/core_mechanics/skills/skill_observation\|OBSERVATION]] | [[wits_attr\|WITS]]         |
| [[dark_canals/mechanics/core_mechanics/skills/skill_reason\|REASON]]           | [[wits_attr\|WITS]]         |
| [[dark_canals/mechanics/core_mechanics/skills/skill_appeal\|APPEAL]]           | [[empathy_attr\|EMPATHY]]   |
| [[dark_canals/mechanics/core_mechanics/skills/skill_insight\|INSIGHT]]         | [[empathy_attr\|EMPATHY]]   |
| [[dark_canals/mechanics/core_mechanics/skills/skill_connections\|CONNECTIONS]] | [[empathy_attr\|EMPATHY]]   |

