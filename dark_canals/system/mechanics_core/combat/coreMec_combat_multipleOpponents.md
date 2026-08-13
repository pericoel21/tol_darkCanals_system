---
tags:
  - combat
  - core
  - mechanic
aliases:
  - Multiple Opponents
  - Outnumbering
  - Outnumbered
connections:
description: Having multiple characters ganging on one enemy gives them the advantage, but still gets resolved with one single roll
---
# `= this.file.aliases[0]`
> `= this.description`.

## Modified Attack Roll
When NPCs attack or get attacked by one PC, the PC uses a [[coreMec_skills|Skill]] as if [[coreMec_combat_melee|attacking or defending]] from a single opponent, but the result of the roll is interpreted differently:
1. Remove dice due to [[stat_stress|Stress]] as normal.
2. Interpret the [[coreMec_rollResolution|Roll as normal]] (using the two highest dice). This is how the first attacker or defender performs against the PC.
3. Remove the highest die (one of the two used in the previous step).
4. Interpret the roll withouth that die. This is how the second attacker or defender performs against the PC.
5. Keep removing one die per attacker, and interpreting the [[coreMec_rollResolution|Roll]], for how many attackers or defenders there are.

### Interpreting Injuries
In the situation where the PC is being attacked, only the [[coreMec_combat_melee|attack]] with the highest [[coreMec_injury|Injury]] counts.

### Helping other PC
If two or more PCs participate in an [[coreMec_combat_melee|attack]] against multiple opponents, the second PC to declare their action counts as performing a [[coreMec_helping|Helping action]].