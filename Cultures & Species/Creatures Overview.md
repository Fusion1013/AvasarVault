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
%% DATAVIEW_PUBLISHER: end %%