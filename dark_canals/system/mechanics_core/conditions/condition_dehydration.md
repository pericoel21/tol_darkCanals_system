---
tags:
  - condition
  - mechanic
  - core
aliases:
  - Dehydration
  - Dehydration Condition
connections:
  - "[[attribute_agility|AGILITY]]"
description: Lack of water that affects a character's strength
---
# `= this.file.aliases[0]`
Associated [[mechanic_attributes|Attribute]]: `=this.connections[0]`
> `= this.description`.

Every day, at [[mechanic_watches|Daybreak]], PCs suffer a point of [[condition_dehydration|Dehydration]]. It does not matter how much the Character has drunk in the previous day.

For each ration of water, the Character reduces the Dehydration [[mechanic_conditions|Condition]] by one. This is handled separately to any water consumed to recover [[stat_stamina|Stamina]].