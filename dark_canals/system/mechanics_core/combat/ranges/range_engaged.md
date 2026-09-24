---
tags:
  - range-band
  - core
  - combat
aliases:
  - Engaged Range
  - Engaged Distance
  - Engaged
connections:
  - "[[combat_distance|Distances]]"
  - "[[combat_engagedStatus|Engaged Status]]"
  - "[[combat_disengage|Disengaging]]"
description: Close enough to stab
zone-relation: "Engaged combatants are in the same Zone"
index: 0
medieval-distance: A Stride
ft: Few
meters: Few
---
# `= this.file.aliases[0]`
> `= this.description`.

_Zone relation:_ `=this.zone-relation`.

| Medieval distance         | Meters         | Ft.        |
| ------------------------- | -------------- | ---------- |
| `=this.medieval-distance` | `=this.meters` | `=this.ft` |

> See [[combat_engagedStatus]]