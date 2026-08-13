---
tags:
  - combat
  - core
  - mechanic
aliases:
  - Disengage
  - Disengaging
connections:
description: A character that retires from a melee might suffer attacks from enemies they're engaged in combat with
---
# `= this.file.aliases[0]`
> `= this.description`.

When a character **moves further from [[coreMec_combat_distance|Engaged range]]** with an enemy, that enemy might attack the character.

After a Disengage attack is performed (successful or not), **no other [[coreMec_combat_reactionsAndCounteractions|Reactions or Counteractions]] can be taken.**

## PC Disengagement
If a PC wants to retreat from [[coreMec_combat_distance|Engaged Range]] with an enemy, or move past an enemy within striking distance, [[coreMec_rollResolution|Roll]] [[skill_mobility|MOBILITY]].


| Roll                                                         | Result                                                                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------- |
| Success                                                      | Move freely.                                                                                |
| Partial Success                                              | Enemy hits the PC with a [[coreMec_combat_melee#Result of the Attack Roll\|Glancing Blow]]. |
| Fail                                                         | Enemy hits the PC                                                                           |
| Fail by two [[coreMec_degreesOfSuccess\|Degrees of Success]] | Enemy hits the PC with a [[coreMec_combat_melee#Result of the Attack Roll\|Heavy Blow]].    |
## Enemy Disengagement
If an enemy attempts to Disengage or move past a PC, the PC makes an [[coreMec_combat_melee|Attack]], with the [[coreMec_difficulty|Difficulty]] set by the enemy's [[skill_mobility|MOBILITY]].
