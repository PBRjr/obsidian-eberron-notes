```dataview
TABLE cr as "CR", size, type, alignment
FROM "Campaign Notes/Statblocks"
WHERE cr
SORT type ASC
```

```dataview
TABLE length(rows) as "Total Statblocks"
FROM "Campaign Notes/Statblocks"
GROUP BY ""
```

```dataview
TABLE cr as "CR", size, type, alignment
FROM "Campaign Notes/Statblocks"
WHERE cr
GROUP BY type
SORT type ASC
```