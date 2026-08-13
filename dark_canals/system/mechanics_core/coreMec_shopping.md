---
tags:
  - core
  - mechanic
aliases:
  - Shopping
connections:
description: Spending coin, not GM dependant
---
# `= this.file.aliases[0]`
> `= this.description`.
To buy stuff, a PC must be in a [[coreMec_settlements|Settlement]] and spend at least one [[coreMec_watches|Watch]].

## Finding Goods & Services
As long as conditions are met, rolls for Shopping can be done withouth the GM's overview.

To find a merchant or a vendor while in a settlement, spend one [[coreMec_watches|Watch]] (must be morning or afternoon) and [[coreMec_rollResolution|Roll]] [[skill_connections|CONNECTIONS]].

The [[coreMec_difficulty|Difficulty]] is determined by the size of the [[coreMec_settlements|Settlement]].

| Size          | Difficulty  |
| ------------- | ----------- |
| Tiny Hammlet  | `Very Hard` |
| Rural Village | `Hard`      |
| Town          | `Average`   |
| City          | `Easy`      |
| Capital City  | `Very Easy` |

If the PC succeeds on the [[coreMec_rollResolution|Roll]], they find a merchant who has any item associated with their trade, or a vendor who can perform their trade service.

If the PC fails, thet can try again in the next [[coreMec_watches|Watch]]that is not evening or night.

The [[coreMec_rollResolution|Roll]] to find merchants must be done each time.
> The merchant you find could have been a travelling merchant, or the established ones may be shut, or out of stock. 

## Vendors, Goods & Services

| Vendors           | Goods                                                                                                                                                                                                                                                                                                                        | Services                                                                                                                |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| General Merchant  | [[item_starterKit\|Starter Kit]], [[item_survivalistKit\|Survivalist Kit]], [[item_dungeoneersKit\|Dungeoneer’s Kit]], [[item_performersKit\|Performer’s Kit]], [[items_snowKit\|Snow Kit]], [[item_huntersKit\|Hunter’s Kit]], [[item_climbersKit\|Climber’s Kit]],[[item_craftmansKit\|Craftsman’s Kit]], [[tools\|Tools]] | -                                                                                                                       |
| Surgeon           | [[items_surgeonKit\|Surgeon Kit]]                                                                                                                                                                                                                                                                                            | [[medicalCare\|Medical Care]], [[skill_surgery\|SURGERY]] [[coreMec_skillTraining\|Training]]                           |
| Blacksmit         | [[items_smithsKit\|Smith's Kit]], [[tools\|Tools]]                                                                                                                                                                                                                                                                           | [[weapon\|Weapons]] / [[armor\|Armor]] [[repair\|Repair]], [[skill_techne\|TECHNE]] [[coreMec_skillTraining\|Training]] |
| Weapon Smith      | [[items_smithsKit\|Smith's Kit]], [[weapons\|Weapons]]                                                                                                                                                                                                                                                                       | Melee [[weapon\|Weapons]] [[repair\|Repair]], [[skill_fight\|FIGHT]] [[coreMec_skillTraining\|Training]]                |
| Armor Smith       | [[items_smithsKit\|Smith's Kit]], [[armor\|Armor]]                                                                                                                                                                                                                                                                           | [[armor\|Armor]] [[repair\|Repair]], [[skill_physique\|PHYSIQUE]] [[coreMec_tradingFencing]]                            |
| Stables           | [[horse\|Horse]]                                                                                                                                                                                                                                                                                                             | [[horse\|Horse]]                                                                                                        |
| Cartwright        | [[item_cart\|Carts]]                                                                                                                                                                                                                                                                                                         | -                                                                                                                       |
| Bowyer / Fletcher | [[item_bow\|Bows]], [[item_crossbow\|Crossbows]], [[item_arrow\|Arrows]], [[item_quarrel\|Quarrels]], [[item_quiver\|Quivers]], [[item_quarrelBox\|Quarrel Boxes]]                                                                                                                                                           | Ranged [[weapon\|Weapon]] [[repair\|Repair]], [[skill_ballistics\|BALLISTICS]] [[coreMec_skillTraining\|Training]]      |
| Locksmith         | [[item_thievesKit\|Thieves Kit]]                                                                                                                                                                                                                                                                                             | [[skill_techne\|TECHNE]] [[coreMec_skillTraining\|Training]]                                                            |
| Tavern            | [[item_booze\|Booze]]                                                                                                                                                                                                                                                                                                        | [[carousing\|Carousing]], [[skill_appeal\|APPEAL]] [[coreMec_skillTraining\|Training]]                                  |
| Wizard            | Esoteric knick-knacks, [[items_chalk\|Chalk]]                                                                                                                                                                                                                                                                                | [[rituals\|Rituals]], [[skill_reason\|REASON]] [[coreMec_skillTraining\|Training]]                                      |
| Church            | Indulgences                                                                                                                                                                                                                                                                                                                  | [[skill_insight\|INSIGHT]] and [[skill_endure\|ENDURE]] [[coreMec_skillTraining\|Training]]                             |
| Library           | Books                                                                                                                                                                                                                                                                                                                        | [[skill_reason\|REASON]] [[coreMec_skillTraining\|Training]]                                                            |
| Gymnasium         | -                                                                                                                                                                                                                                                                                                                            | [[skill_mobility\|MOBILITY]] and [[skill_physique\|PHYSIQUE]] [[coreMec_skillTraining\|Training]]                       |
| Cartographer      | [[item_map\|Maps]]                                                                                                                                                                                                                                                                                                           | [[skill_observation\|OBSERVATION]] training                                                                             |
| Trader            | [[coreMec_tradingFencing\|Trade Goods]]]                                                                                                                                                                                                                                                                                     | [[skill_connections\|CONNECTIONS]] [[coreMec_skillTraining\|Training]]                                                  |
