## List of Creatures
```dataview
TABLE
creature_type AS Type,
environment AS Environment,
image AS Image
FROM #creature
WHERE creature_type != "TEMPLATE"
SORT creature_type + file.name ASC
```
