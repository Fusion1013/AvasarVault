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
> | **Region** | [[Elisus Overview\|Elisus]] |
> | **Capital** | [[Chalayan, The city of a Thousand Rivers]] |
> ###### Society
> | **Demonym** |  |
> | - | - |
> | **Races** | Humans, Halflings, Dwarves |
> | **Languages** | [[Thüma]] |
> | **Religions** | [[Merstur - the Unbroken Tide\|Merstur]], [[Ogrun - the Scarlet Champion\|Ogrun]] |
> | **Estimated Population** | 00 |
> ###### Politics
> | **Type** | Polytheocratic Republic |
> | - | - |
> | **Ruler** | [[The Grand Synod of Ohkyr]] |
> | **Allegiances** |  |

*"QUOTE"*
# Overview
Ohkyr is a coastal nation occupying the northern coasts of [[Elisus Overview|Elisus]], bordering the [[City-State of Drufali Overview|City-State of Drufali]], the [[Saxum Sovereignty Overview|Saxum Sovereignty]] as well as [[Storms Reach Overview|Storms Reach]]. Its capital is [[Chalayan, The city of a Thousand Rivers]]. The nation is a Polytheocratic Republic, with a majority of the population dedicated to [[Merstur - the Unbroken Tide]], or [[Ogrun - the Scarlet Champion]]. Ohkyr is a nation known for its powerful militia and navy, known as [[The Sanctified Host]].
# History
The nation has a rocky history, riddled with corruption and greed within the top levels of the institution. The [[Ohkyr Dominion Overview|Ohkyr Dominion]] was officially formed in 212 APC, though the cities and people living there have existed for far longer. Before [[Ohkyr Dominion Overview|Ohkyr]] was formed, the area was home to a number City-States warring to each claim the gods' favour.

This conflict between cities lasted until the 2nd century, when [[High Priest Varlen of the Shattered River]] forged an unprecedented alliance with [[Warlord Kezrah Ironwake]], uniting the rival faiths of [[Merstur - the Unbroken Tide|Merstur]] and [[Ogrun - the Scarlet Champion|Ogrun]]. This accord became known as [[The Concord of Salt and Steel]] and founded the [[Ohkyr Dominion Overview|Ohkyr Dominion]] with its capital [[Chalayan, The city of a Thousand Rivers]].

To cement this unity, this alliance of faith, the two commissioned a citadel for the city of [[Chalayan, The city of a Thousand Rivers|Chalayan]], where faith and governance could exist together. The citadel became known as [[Chalayan, The city of a Thousand Rivers#The Hall of Echoes|The Hall of Echoes]].

The [[1167APC - Taundor Cataclysm|Taundor Cataclysm in 1167APC]] rocked the nation. Many cities and towns on the western side of the continent were affected by the disaster, many destroyed, many more abandoned. The force of the collision caused mountains to rise and cracks to form in the ground. Earthquakes wracked the western regions of the nation for many years after, making the area close to the newly formed mountains uninhabitable. It took over half a century for the land to settle, and people could begin to venture west once more.

When people from the nation begun exploring the new lands west of the mountains, they found a new people inhabiting the region. They found the [[Saxum Sovereignty Overview|Saxum Sovereignty]]. As [[Ohkyr Dominion Overview|Ohkyr]] was still dealing with the consequences from the cataclysm, they made the decision to forge an alliance. It took them until [[1276 APC - Invasion of Saxum|1276APC]] to attempt to claim the new land, when the [[Ohkyr Dominion Overview|Ohkyr Dominion]] attempted an invasion of [[Saxum Sovereignty Overview|Saxum]] using their superior fleet. They managed to take [[Havdal, City of Pearls]], but was pushed back after they laid siege to [[Gulstad, City of Gold|Gulstad]]. The invasion ended in a failure, and [[Saxum Sovereignty Overview|Saxum]] pushed back to the original borders. In the years to follow, [[Saxum Sovereignty Overview|Saxum]] conducted raids into [[Ohkyr Dominion Overview|Ohkyr]], in an attempt to deter the nation to attempt further attacks. In the year [[1279APC]] a treaty was signed between [[Ohkyr Dominion Overview|Ohkyr]] and [[Saxum Sovereignty Overview|Saxum]]. This treaty was heavily in favour of [[Saxum Sovereignty Overview|Saxum]], preventing any further attacks and forcing [[Ohkyr Dominion Overview|Ohkyr]] to help with restorations.
# Culture
# Cities
```dataview
TABLE 
population AS "Population",
choice(population <= 80, "Thorp", choice(population <= 400, "Hamlet", choice(population <= 900, "Village", choice(population <= 2000, "Small Town", choice(population <= 5000, "Large Town", choice(population <= 12000, "Small City", choice(population <= 25000, "Large City", choice(population > 25000, "Metropolis", "Unknown")))))))) AS "Size"
FROM #city
WHERE nation = "Ohkyr"
SORT file.name ASC
```
# People
```dataview
TABLE description AS "Description", race AS "Race", (age + " years") AS "Age" FROM #major_person AND #alive
WHERE nation = "Ohkyr Dominion"
```
# Organizations
```dataview
TABLE 
leaders AS "Leaders",
members AS "Members",
formed AS "Date Formed"
FROM #organization
WHERE nation = "Ohkyr Dominion"
```
# Economy

## Currency

# Religion
The two main religions of [[Ohkyr Dominion Overview|Ohkyr]] are dedicated to [[Merstur - the Unbroken Tide|Merstur]] and [[Ogrun - the Scarlet Champion|Ogrun]]. Other faiths are not strictly outlawed, though they are extremely uncommon and frowned at among the general populace.

The theological background of these two faiths make up the ruling body of [[Ohkyr Dominion Overview|Ohkyr]].
# Military Power
![[LargeBattleship.jpg]]
Ohkyr has one of the largest navies on the continent and dominates a large part of the surrounding ocean. They have trained clerics specialized on taming the ocean to their will. The people of Ohkyr are signed into the army at an early age, forcing them to complete a mandatory period of military service. The living conditions of army life are not great; though not terrible either.
# Language
Main language is called [[Thüma]]. Use Turkish references when naming things.
# Timeline
```dataview
TABLE WITHOUT ID "[[" + file.name + "]]" + choice(contains(file.etags, "#city_founding"), " `far:Flag`", "") + choice(contains(file.etags, "#discovery"), " `far:Lightbulb`", "") + choice(contains(file.etags, "#nation_founding"), " `ris:Flag`", "") + choice(contains(file.etags, "#law"), " `ris:Book2`", "") AS "Event", description AS "Description" FROM #timeline_event WHERE contains(nation, "NATION") SORT date DESC
```
