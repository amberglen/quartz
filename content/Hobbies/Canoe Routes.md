---
Created: 2025-01-05 11:56
tags:
  - canoe
  - algonquin
---
```dataview
table without ID
file.link as "Route",
access-point as "Access Point",
route-time as "Time",
row["Portage (km)"] as "Portage (km)",
trip-type as "Trip Type", Days,
choice(Completed, "☑", "☐") as Completed
from #canoe/routes AND !"Templates"
sort access-point asc
```
