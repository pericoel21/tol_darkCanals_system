---
tags:
  - condition
  - core
  - mechanic
aliases:
  - Starvation
  - Starvation Condition
connections:
  - "[[attr_strength|STRENGTH]]"
description: Lack of feeding that affects a character's strength
---
# `= this.file.aliases[0]`
Associated [[coreMec_attributes|Attribute]]: `=this.connections[0]`
> `= this.description`.

Every day, at [[coreMec_watches|Daybreak]], PCs suffer a point of Starvation. It does not matter how much the Character has eaten in the previous day.

For each [[item_ration|Ration of Food]] consumed, the Character reduces the Starvation [[coreMec_conditions|Condition]] by one. This is handled separately to any food consumed to recover [[stat_stamina|Stamina]] by [[coreMec_eating|Eating]].