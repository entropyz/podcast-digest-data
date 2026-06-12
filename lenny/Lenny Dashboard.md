# Lenny's Podcast Dashboard

## Recent Episodes
```dataview
TABLE guest, companies, date, duration
FROM #lenny-podcast
SORT date DESC
LIMIT 20
```

## By Tag: Product
```dataview
TABLE guest, companies, date
FROM #lenny-podcast AND #product
SORT date DESC
```

## By Tag: Growth
```dataview
TABLE guest, companies, date
FROM #lenny-podcast AND #growth
SORT date DESC
```

## All Guests
```dataview
TABLE companies, topic, date
FROM #lenny-podcast
WHERE type = "interview"
SORT guest ASC
```

## Most Viewed
```dataview
TABLE guest, companies, views, date
FROM #lenny-podcast
SORT views DESC
LIMIT 20
```
