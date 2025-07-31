# Creatures Overview
## List of Creatures
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE
creature_type AS Type,
environment AS Environment,
image AS Image
FROM #creature
WHERE creature_type != "TEMPLATE"
SORT creature_type + file.name ASC
```
%%

| File                                                                                                                               | Type        | Environment                                                                                                                                           | Image                                                     |
| ---------------------------------------------------------------------------------------------------------------------------------- | ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [[Cultures & Species/Birds/Chrawk.md\|Chrawk]]                                                                                     | Bird        | \-                                                                                                                                                    | \-                                                        |
| [[Cultures & Species/Miscelaneous/Centirat.md\|Centirat]]                                                                          | Cave Vermin | [[Environment/Environment Types/Caves.md\|Caves]]                                                                                                     | \-                                                        |
| [[Cultures & Species/Miscelaneous/Vermilginu.md\|Vermilginu]]                                                                      | Cave Vermin | [[Environment/Environment Types/Caves.md\|Caves]]                                                                                                     | ![[Attachements/Creatures/Vermilginu2.png\|100]]          |
| [[Cultures & Species/Dragons/Silver and Iron Variants - Dragonback Mountains.md\|Silver and Iron Variants - Dragonback Mountains]] | Dragon      | \-                                                                                                                                                    | \-                                                        |
| [[Cultures & Species/Mushrooms/Hikseta.md\|Hikseta]]                                                                               | Mýkite      | [[Environment/Environment Types/Caves.md\|Caves]]                                                                                                     | ![[Attachements/Creatures/MushroomWithCrossbow.png\|100]] |
| [[Cultures & Species/Mushrooms/Moogshrooms.md\|Moogshrooms]]                                                                       | Mýkite      | [[Environment/Environment Types/Forest.md\|Forest]]                                                                                                   | ![[Attachements/Creatures/Moogshroom.png\|100]]           |
| [[Cultures & Species/Mushrooms/Myconid Colonizers.md\|Myconid Colonizers]]                                                         | Mýkite      | [[Environment/Environment Types/Caves.md\|Caves]]                                                                                                     | ![[Attachements/Creatures/UndeadMushroomfolk.png\|100]]   |
| [[Cultures & Species/Mushrooms/Puffshroom.md\|Puffshroom]]                                                                         | Mýkite      | [[Environment/Environment Types/Caves.md\|Caves]]                                                                                                     | ![[Attachements/Plants/ExplodingMushroom.png\|100]]       |
| [[Cultures & Species/Worldbeasts/Aonus, the Wandering Giant.md\|Aonus, the Wandering Giant]]                                       | Worldbeast  | <ul><li>[[Cosmology/Inner Planes/Aurora Ortus.md\|Aurora Ortus]]</li></ul>                                                                           | ![[Attachements/Creatures/AonusHead.png\|100]]            |
| [[Cultures & Species/Worldbeasts/Hiosu, the Wandering Kingdom.md\|Hiosu, the Wandering Kingdom]]                                   | Worldbeast  | <ul><li>Material Plane</li><li>[[Environment/Environment Types/Ocean.md\|Ocean]]</li></ul>                                                           | ![[Attachements/Creatures/MovingTheKingdom.jpg\|100]]     |
| [[Cultures & Species/Worldbeasts/Nyaricath, the Star-Spawned Horror.md\|Nyaricath, the Star-Spawned Horror]]                       | Worldbeast  | \-                                                                                                                                                    | ![[Attachements/Creatures/PolyphemusGasGiant.jpg\|100]]   |
| [[Cultures & Species/Worldbeasts/Thalassa, the Abyssal Maw.md\|Thalassa, the Abyssal Maw]]                                         | Worldbeast  | <ul><li>[[Environment/Environment Types/Ocean.md\|Ocean]]</li><li>[[Cosmology/Inner Planes/Terozin, Plane of Weather & Seas.md\|Terozin]]</li></ul> | ![[Attachements/Creatures/ThalassiaAbyssalMaw.jpg\|100]]  |

%% DATAVIEW_PUBLISHER: end %%
## Creatures by Environment
### Forest
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE
creature_type AS Type,
image AS Image
FROM #creature
WHERE contains(join(environment, ""), "Caves")
```
%%

| File                                                                       | Type        | Image                                                     |
| -------------------------------------------------------------------------- | ----------- | --------------------------------------------------------- |
| [[Cultures & Species/Mushrooms/Puffshroom.md\|Puffshroom]]                 | Mýkite      | ![[Attachements/Plants/ExplodingMushroom.png\|100]]       |
| [[Cultures & Species/Mushrooms/Myconid Colonizers.md\|Myconid Colonizers]] | Mýkite      | ![[Attachements/Creatures/UndeadMushroomfolk.png\|100]]   |
| [[Cultures & Species/Mushrooms/Hikseta.md\|Hikseta]]                       | Mýkite      | ![[Attachements/Creatures/MushroomWithCrossbow.png\|100]] |
| [[Cultures & Species/Miscelaneous/Vermilginu.md\|Vermilginu]]              | Cave Vermin | ![[Attachements/Creatures/Vermilginu2.png\|100]]          |
| [[Cultures & Species/Miscelaneous/Centirat.md\|Centirat]]                  | Cave Vermin | \-                                                        |

%% DATAVIEW_PUBLISHER: end %%
### Caves
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE
creature_type AS Type,
image AS Image
FROM #creature
WHERE contains(join(environment, ""), "Forest")
```
%%

| File                                                         | Type   | Image                                           |
| ------------------------------------------------------------ | ------ | ----------------------------------------------- |
| [[Cultures & Species/Mushrooms/Moogshrooms.md\|Moogshrooms]] | Mýkite | ![[Attachements/Creatures/Moogshroom.png\|100]] |

%% DATAVIEW_PUBLISHER: end %%
### Ocean
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE
creature_type AS Type,
image AS Image
FROM #creature
WHERE contains(join(environment, ""), "Ocean")
```
%%

| File                                                                                             | Type       | Image                                                    |
| ------------------------------------------------------------------------------------------------ | ---------- | -------------------------------------------------------- |
| [[Cultures & Species/Worldbeasts/Thalassa, the Abyssal Maw.md\|Thalassa, the Abyssal Maw]]       | Worldbeast | ![[Attachements/Creatures/ThalassiaAbyssalMaw.jpg\|100]] |
| [[Cultures & Species/Worldbeasts/Hiosu, the Wandering Kingdom.md\|Hiosu, the Wandering Kingdom]] | Worldbeast | ![[Attachements/Creatures/MovingTheKingdom.jpg\|100]]    |

%% DATAVIEW_PUBLISHER: end %%