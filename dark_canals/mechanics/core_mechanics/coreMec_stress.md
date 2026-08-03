---
tags:
  - core
  - stat
aliases:
  - Stress
connections:
description: Representation of factors not under conscious control of a character
---
# `= this.file.aliases[0]`
> `= this.description`.

## Gaining Stress
A Character gains one Stress each time they fail a [[coreMec_rollResolution|Roll]].

## Rolling with stress
Whenever a PC rolls for a Skill, a number of dice in the pool are substituted by Stress Dice.

### Stress Dice
- Are dice in a different color to the base ones, to differentiate them.
- They work like base dice in terms of parsing the outcome of a [[coreMec_rollResolution|Roll]].
- Therefore, Stress Dice can be Success Dice.
- In addition, each dice with an outcome of 1 causes a Stress Response (regardless if that die is a Success Dice).

### Pool Lower than Current Stress
If a base dice pool for a [[coreMec_rollResolution|Roll]] is lower than the PC's current Stress, the dice pool for that [[coreMec_rollResolution|Roll]] is a number of dice equal to the Stress, all dice being Stress Dice.

Note: This way, Stress allows you to essentially ignore the effects of [[coreMec_attributeDamage|Attribute Damage]]

> This means that acting under pressure or with adrenaline pumping might cause a Character to push beyond their physical capabilities.

# Stress Response
When performing a [[coreMec_rollResolution|Roll]], for each 1 roll on a Stress Dice, another dice is cancelled, in decreasing order from the highest result.

If a [[coreMec_rollResolution|Roll]] fails because of this, the fail was caused because the Character Panicked.

It is possible to spend [[coreMec_resolve|Resolve]] to cancel rolled 1s in a one-per-one basics ([[coreMec_resolve#Keeping Your Cool|Keeping Your Cool]]). This can go as far as canceling a Stress Response.

> It’s still up to the playerto role-play how their character handles Stress whether a Stress Response happens or not.

## Recovering Stress

### By Relaxing
For every hour a Character spends relaxing in a safe place, they decrease their Stress by 1.

#### Safe Place
Camping in untamed wilderness or in a dungeon, where monsters lurk and can set upon you at any moment, does not count as a "safe place".

It can be made a Safe Place by either:
- [[making_camp|Making Camp]] and establishing watches.
- Using recreational substances like booze or pipeweed.

#### Sleeping
Sleeping does not count as ‘relaxing’ in this case.
> Consider if you come home from work and go straight to bed without winding down first - without a chance to decompress, your levels of Stress are going to build up over time.

### By Another Character's Appeal
Once per [[watch|Watch]], if another Character makes a successful [[skill_appeal|APPEAL]] roll, they can reduce the Character Stress by 1 (cannot be performed on oneself).

 