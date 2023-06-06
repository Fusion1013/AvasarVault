## Major Events
Below follows a list of only the major events that have taken place throughout the history of Avasar.
```dataview
TABLE WITHOUT ID
date + " - " + title AS "Event",
nation AS "Nation",
description AS "Description"
FROM #timeline_event AND (#major_event OR #world_event) 
WHERE title != ""
SORT data DESC
```
## Events
Below follows a list of all events, minor and major, that have taken place throughout the history of Avasar.
```dataview
TABLE WITHOUT ID
date + " - " + title AS "Event",
nation AS "Nation",
description AS "Description"
FROM #timeline_event 
WHERE title != ""
SORT data DESC
```
