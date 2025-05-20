---
aliases:
  - Ohkyr
  - Ohkyr Dominion
tags:
  - nation
todo:
  - Fill Out
  - Reformat "Military Power" Section
editors: Fusion
---
> [!infobox|right]
> # Ohkyr Dominion
> ![[OhkyrDominionV3.png]]
> ###### Geography
> | **Aliases** |  |
> | - | - |
> | **Type** | Nation |
> | **Region** | [[Elisus Overview\|Elisus]] |
> | **Capital** | [[Chalayan, The city of a Thousand Rivers]] |
> ###### Society
> | **Demonym** |  |
> | - | - |
> | **Races** | Humans, Halflings, Dwarves |
> | **Languages** | [[Thüma]] |
> | **Religions** | [[Merstur - the Unbroken Tide\|Merstur]], [[Ogrun - the Scarlet Champion\|Ogrun]] |
> ###### Politics
> | **Type** | Polytheocratic Republic |
> | - | - |
> | **Ruler** |  |
> | **Allegiances** |  |

*"QUOTE"*
# Overview
Ohkyr is a coastal nation occupying the northern coasts of [[Elisus Overview|Elisus]], bordering the [[City-State of Drufali Overview|City-State of Drufali]] as well as [[Storms Reach Overview|Storms Reach]]. Its capital is [[Chalayan, The city of a Thousand Rivers]]. The nation is a Polytheocratic Republic, with a majority of the population dedicated to [[Merstur - the Unbroken Tide]], or [[Ogrun - the Scarlet Champion]]. Ohkyr is a nation known for its powerful militia and navy, known as [[The Sanctified Host]].
# History
The nation has a rocky history, riddled with corruption and greed within the top levels of the institution. The [[Ohkyr Dominion Overview|Ohkyr Dominion]] was officially formed in 212 APC, though the cities and people living there have existed for far longer. Before [[Ohkyr Dominion Overview|Ohkyr]] was formed the area was home to a number City-States, warring to each claim the gods' favour.

This conflict lasted until the 2nd century, when [[High Priest Varlen of the Shattered River]] forged an unprecedented alliance with [[Warlord Kezrah Ironwake]], uniting the rival faiths of [[Merstur - the Unbroken Tide|Merstur]] and [[Ogrun - the Scarlet Champion|Ogrun]]. This accord became known as [[The Concord of Salt and Steel]] and founded the [[Ohkyr Dominion Overview|Ohkyr Dominion]] with its capital [[Chalayan, The city of a Thousand Rivers]].

To cement this unity, this alliance of faith, the two commissioned a citadel for the city of [[Chalayan, The city of a Thousand Rivers|Chalayan]], where faith and governance could exist together. The citadel became known as [[Chalayan, The city of a Thousand Rivers#The Hall of Echoes|The Hall of Echoes]].
# Religion
The two main religions of [[Ohkyr Dominion Overview|Ohkyr]] are dedicated to [[Merstur - the Unbroken Tide|Merstur]] and [[Ogrun - the Scarlet Champion|Ogrun]]. Other faiths are not strictly outlawed, though they are extremely uncommon among the general populace.
# Cities
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE 
population AS "Population",
choice(population <= 80, "Thorp", choice(population <= 400, "Hamlet", choice(population <= 900, "Village", choice(population <= 2000, "Small Town", choice(population <= 5000, "Large Town", choice(population <= 12000, "Small City", choice(population <= 25000, "Large City", choice(population > 25000, "Metropolis", "Unknown")))))))) AS "Size"
FROM #city
WHERE nation = "Ohkyr"
SORT file.name ASC
```
%%

| File                                                                                                                                 | Population | Size       |
| ------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ---------- |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Chalayan, The city of a Thousand Rivers.md\|Chalayan, The city of a Thousand Rivers]] | 130000     | Metropolis |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Deyruk.md\|Deyruk]]                                                                   | 37000      | Metropolis |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Gelthurun, Eye of the North.md\|Gelthurun, Eye of the North]]                         | 5600       | Small City |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Halimeth.md\|Halimeth]]                                                               | 3200       | Large Town |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Halzarin.md\|Halzarin]]                                                               | 7800       | Small City |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Kesiyra.md\|Kesiyra]]                                                                 | 42000      | Metropolis |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Meztara.md\|Meztara]]                                                                 | 24000      | Large City |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Sarhuna.md\|Sarhuna]]                                                                 | 7800       | Small City |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Seyvarin.md\|Seyvarin]]                                                               | 10300      | Small City |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Uskedram.md\|Uskedram]]                                                               | 12400      | Large City |
| [[Major Locations/Elisus/Ohkyr Dominion/Cities/Velmira, City of Watchful Waters.md\|Velmira, City of Watchful Waters]]               | 48000      | Metropolis |

%% DATAVIEW_PUBLISHER: end %%
# Minor Cities
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE description AS "Description"
FROM #city/minor 
WHERE nation = "Ohkyr"
```
%%
%% DATAVIEW_PUBLISHER: end %%
# Military Power
![[LargeBattleship.jpg]]
Ohkyr has one of the largest navies on the continent and dominates a large part of the surrounding ocean. They have trained clerics specialized on taming the ocean to their will. The people of Ohkyr are signed into the army at an early age, forcing them to complete a mandatory period of military service. The living conditions of army life are not great; though not terrible either.
# Language
Main language is called [[Thüma]]. Use Turkish references when naming things.