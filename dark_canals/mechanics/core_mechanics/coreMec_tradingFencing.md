---
tags:
  - core
  - mechanic
aliases:
  - Trading & Fencing
  - Trading
  - Fencing
connections:
description: Selling artefacts and trading goods depends on how well connected the seller is, and the size of the settlement
---
# `= this.file.aliases[0]`
> `= this.description`.

## Trade Goods vs. Artefacts

| Trade Goods                                                                                              | Artefacts                          |
| -------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| Can be bought.                                                                                           | Must be found by adventuring       |
| Must be Traded in "cartloads"; the amount worth trading is too big.                                      | A single artefact can be Fenced    |
| Price varies from one Settlement to another, depending on the market for those goods.                    | Price does not depend on location. |
| Must be taken to a different Settlement than the one where the goods were initially bought to sell them. | Might be sold anywhere.            |

> A single saleable unit of Trade Goods is too large for any person to carry, namely, a cartload. If you don’t have a cart (or other form of transportation capable of carrying one or more cartloads of trade goods), then you can’t transport enough to earn you any COIN!

## Trade Goods Buying Process
- Spend a [[coreMec_watches|Watch]] looking for a seller.
- Roll [[skill_connections|CONNECTIONS]]. The difficulty depends on the size of the [[coreMec_settlements|Settlement]].

### Result of the Roll
#### Failing the Roll
There is no one in the current [[coreMec_settlements|Settlement]] who wants to sell, has the quantity, or likes the named price for any the Trade Goods.
- You can try in a different [[coreMec_settlements|Settlement]].
- You can try again in the current [[coreMec_settlements|Settlement]] in one week’s time.

#### Succeeding the Roll
Exchange one [[coreMec_coin|COIN]] for a unit of Trade Goods (a "cartload").

## Selling or Fencing Process
- Spend a [[coreMec_watches|Watch]] looking for a buyer.
- Roll [[skill_connections|CONNECTIONS]]. The difficulty depends on the size of the [[coreMec_settlements|Settlement]].

### Result of the roll
#### Failing the Roll
There is no one in the current [[coreMec_settlements|Settlement]] who wants to buy Artefact or the Trade Goods (or can afford to).
- You can try in a different [[coreMec_settlements|Settlement]].
- You can try again in the current [[coreMec_settlements|Settlement]] in one week’s time.

#### Succeeding the Roll
You may exchange the Artefact or the Trade Goods for one [[coreMec_coin|COIN]], doubling the [[coreMec_coin|COIN]] for each level of success higher than the Difficulty, to a maximun of four [[coreMec_coin|COIN]].

| Degree of Success | Coin |
| ----------------- | ---- |
| 0                 | 1    |
| 1                 | 2    |
| 2+                | 4    |

### Holding Out for More
It is not mandatory to part with the Artefact or the Trade Goods after the Roll.
> You might feel you could have rolled better on your [[skill_connections|CONNECTIONS]].

After refusing an offer, the PC might spend another [[coreMec_watches|Watch]] and roll again. Each time an offer is refused, the [[coreMec_difficulty|Difficulty]] is raised by one step for that Artefact or those Goods.

After one week, the [[coreMec_difficulty|Difficulty]] resets to the base.

### Exchanging the Artefact or the Goods
An Artefact or a unit of Trade Goods can always be exchange for something worth one [[coreMec_coin|COIN]] at a location where such trade could happen.

## Difficulty per Settlement
### Difficulty by Size 
> Bigger settlements have more potential buyers and more rich individuals.

| Size          | Difficulty  |
| ------------- | ----------- |
| Tiny Hammlet  | `Very Hard` |
| Rural Village | `Hard`      |
| Town          | `Average`   |
| City          | `Easy`      |
| Capital City  | `Very Easy` |

### Difficulty by Demand
In the case of Trade Goods only, demand for a product in a given settlement can make the [[coreMec_difficulty|Difficulty]] for the selling [[coreMec_rollResolution|Roll]] `Easier`.