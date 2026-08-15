---
tags:
  - core
  - mechanic
aliases:
  - Conditions
  - Condition
connections:
description: Ways a PC's physical and mental capabilities can be impaired
---
# `= this.file.aliases[0]`
> `= this.description`.

Each Condition has an associated [[mechanic_attributes|Attribute]] which both defines the maximum amount of boxes in that Condition and gets affected by that Condition.

| Condition                         | Attribute                   |
| --------------------------------- | --------------------------- |
| [[condition_starvation\|Starvation]]   | [[attribute_strength\|STRENGTH]] |
| [[condition_exposure\|Exposure]]       | [[attribute_strength\|STRENGTH]] |
| [[condition_dehydration\|Dehydration]] | [[attribute_agility\|AGILITY]]   |
| [[condition_exhaustion\|Exhaustion]]   | [[attribute_wits\|WITS]]         |
| [[condition_burnout\|Burnout]]         | [[attribute_empathy\|EMPATHY]]   |

## Tracking Conditions in the [[character_sheet|Character Sheet]]
- Black out any Condition box outside the maximum.
- Track the Condition by crossing a box each time the Condition is added, from top to bottom, and from left to right.

## Disease and Poison
Rather than separate Conditions for each of these, diseases and poisons simply cause one of the other Conditions, or an Injury. A disease that causes fever might just count as Exposure requiring you to keep warm to recover, or a poison that you’ve imbibed might cause an Injury to the torso at a level proportional to the toxicity of the poison. The difference here is that a Condition only goes
away when certain conditions are met, whereas an Injury will go away given enough time, so use these as a guide when deciding the effects of diseases and poisons.