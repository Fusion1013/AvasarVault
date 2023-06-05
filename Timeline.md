## Events
Below follows a list of all events that have taken place throughout the history of Avasar.
```dataview
TABLE WITHOUT ID
date + " - " + title AS "Event",
nation AS "Nation",
description AS "Description"
FROM #timeline_event 
WHERE title != ""
SORT data DESC
```
