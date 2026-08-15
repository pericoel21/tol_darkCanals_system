---
tags:
  - core
  - stat
aliases:
  - Stress
  - Stress Response
connections:
description: Representation of factors not under conscious control of a character
---
# `= this.file.aliases[0]`
> `= this.description`.

## Gaining Stress
A Character gains one Stress each time they fail a [[mechanic_rollResolution|Roll]].

## Rolling with stress
Whenever a PC rolls for a Skill, a number of dice in the pool are substituted by Stress Dice.

### Stress Dice
- Are dice in a different color to the base ones, to differentiate them.
- They work like base dice in terms of parsing the outcome of a [[mechanic_rollResolution|Roll]].
- Therefore, Stress Dice can be Success Dice.
- In addition, each dice with an outcome of 1 causes a Stress Response (regardless if that die is a Success Dice).

### Pool Lower than Current Stress
If a base dice pool for a [[mechanic_rollResolution|Roll]] is lower than the PC's current Stress, the dice pool for that [[mechanic_rollResolution|Roll]] is a number of dice equal to the Stress, all dice being Stress Dice.

Note: This way, Stress allows you to essentially ignore the effects of [[mechanic_attributeDamage|Attribute Damage]]

> This means that acting under pressure or with adrenaline pumping might cause a Character to push beyond their physical capabilities.

## Stress Response
When performing a [[mechanic_rollResolution|Roll]], for each 1 roll on a Stress Dice, another dice is cancelled, in decreasing order from the highest result.

If a [[mechanic_rollResolution|Roll]] fails because of this, the fail was caused because the Character Panicked.

It is possible to spend [[stat_resolve|Resolve]] to cancel rolled 1s in a one-per-one basics ([[stat_resolve#Keeping Your Cool|Keeping Your Cool]]). This can go as far as canceling a Stress Response.

> It’s still up to the playerto role-play how their character handles Stress whether a Stress Response happens or not.

## Recovering Stress
Stress might be [[mechanic_recoveringStress|Recovered]] with the help of other Character (by using their [[skill_appeal|APPEAL]]), or by relaxing in a safe place.

## Marking Stress in the [[character_sheet|Character Sheet]]
- Each time Stress is added, mark it with the corresponding number, sequentially.