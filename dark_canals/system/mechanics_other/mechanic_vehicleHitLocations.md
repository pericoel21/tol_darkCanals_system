---
tags:
  - mechanic
  - wip
  - homebrew
aliases:
  - Vehicle Hit Locations
  - Vehicle Hit Location
connections:
description: Hit locations work in the typical way in vehicles, but they have other names and several variations
---
# `= this.file.aliases[0]`
> `= this.description`.

Do a special fuel tank rule?
How do we handle "aimed at the wheel, hit the passenger?"

### Motorbike

| d6  | Location    | Meaning                           | Adjacent to...                        |
| --- | ----------- | --------------------------------- | ------------------------------------- |
| 1   | Engine      | Engine & other mechanical bits    | Hull                                  |
| 2   | Hull        | Body, seat, tail light, handlebar | All others                            |
| 3   | Front wheel | Front wheel                       | Hull                                  |
| 4   | Back wheel  | Back wheel, transmission chain    | Hull, passenger legs, passenger torso |
| 5   | Rider       | Person riding the bike            | See below                             |
| 6   | Fuel Tank   | Catastrophic hit, like the head   | Hull, Engine, Passenger               |

If aiming at the passenger, consider that parts of the bike are also possible hit locations:
- None is adjacent to the head
- One leg might be in cover, hitting the hull instead
- Aiming at the arms might hit the handlebar (hull)

### Tank
Turret is not a location unless you're shooting with another tank at a great distance or something like that.
With firearms, you can just hit the turret, or the tracks, or the body, granting you are not more than Far.