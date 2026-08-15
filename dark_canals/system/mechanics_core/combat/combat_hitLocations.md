---
tags:
  - combat
  - core
  - mechanic
aliases:
  - Hit Locations
  - Hit Location
connections:
description: Determine where an attack lands
---
# `= this.file.aliases[0]`
> `= this.description`.

## Determining Hit Location
When a character attacks another:
1. Attacker **states the body part they are targeting.**
	I**f not specified,** attack targets the **Torso.**
2. The **GM rolls** a `D6`, the **Hit Location Die.**
3. **Compare** the result of the Hit Location Die to the **Hit Location Table.**

### Comparing the Results

| Hit Location Die Outcome                          | Where attack hits |
| ------------------------------------------------- | ----------------- |
| `Nat 6`                                           | Desired location  |
| Desired location's number                         | Desired location  |
| Num. of location adjacent to desired location     | Location rolled   |
| Num. of location not adjacent to desired location | Torso             |
### Adjacency

| Location | Adjacent locations                 |
| -------- | ---------------------------------- |
| Leg      | Other Leg, Arm of that side, Torso |
| Arm      | Other Arm, Head, Torso             |
| Torso    | Everything                         |
| Head     | Torso, Arms                        |
#### Nemotechnics
- The higher the number, the higher up the body.
- Odd numbers are left hand side.
- Three is in the middle, like the torso.

### Hit Location Table

| `D6` | Location  |
| ---- | --------- |
| 6    | Head      |
| 5    | Left Arm  |
| 4    | Right Arm |
| 3    | Torso     |
| 2    | Right Leg |
| 1    | Left Leg  |
