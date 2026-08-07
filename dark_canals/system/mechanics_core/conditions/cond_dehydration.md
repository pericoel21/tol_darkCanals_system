---
tags:
  - condition
  - mechanic
  - core
aliases:
  - Dehydration
  - Dehydration Condition
connections:
  - "[[attr_agility|AGILITY]]"
description: Lack of water that affects a character's strength
---
# `= this.file.aliases[0]`
Associated [[coreMec_attributes|Attribute]]: `=this.connections[0]`
> `= this.description`.

Every day, at [[coreMec_watches|Daybreak]], PCs suffer a point of [[cond_dehydration|Dehydration]]. It does not matter how much the Character has drunk in the previous day.

For each ration of water, the Character reduces the Dehydration [[coreMec_conditions|Condition]] by one. This is handled separately to any water consumed to recover [[stat_stamina|Stamina]].