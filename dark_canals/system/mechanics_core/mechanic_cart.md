---
tags:
  - core
  - mechanic
aliases:
  - Cart
  - Horse Cart
connections:
  - "[[mechanic_tradingFencing|Trading]]"
  - "[[mechanic_horse|Horse]]"
  - "[[trait_horse_cart|Cart Horse]]"
description: Can be pulled by horses to transport goods
---
# `= this.file.aliases[0]`
> `= this.description`.

- Carts cost one [[mechanic_coin|COIN]].
- Can carry a driver, a passenger and [[mechanic_tradingFencing|goods]] (measured in `Cartloads`).
- Cannot travel on [[mechanic_overlandTravel|difficult terrain]] (even pulled by [[trait_horse_pack|pack horses]]).

## Cartload
Amount of trade goods equal to two people and their inventory.

## Minimum & Fast number of Horses
Each cart has a minimum number of [[mechanic_horse|Horses]] it requires:
- Meeting that number means the cart travels `Incumbered` (walking speed).
- Meeting double that number means the cart travels `Unincumbered` (additional [[mechanic_overlandTravel|league]] per day).

## List of Carts

| Cart          | Capacity      | Min. # Horses |
| ------------- | ------------- | ------------- |
| Cart          | 1 `Cartload`  | 1             |
| Wagon         | 2 `Cartloads` | 2             |
| Freight Wagon | 4 `Cartloads` | 4             |
