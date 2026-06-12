# 20VC Dashboard

## Recent Episodes
```dataview
TABLE guest, company, date
FROM #20vc
SORT date DESC
LIMIT 20
```

## By Tag: AI
```dataview
TABLE guest, company, date
FROM #20vc AND #ai
SORT date DESC
```

## By Tag: Fundraising
```dataview
TABLE guest, company, date
FROM #20vc AND #fundraising
SORT date DESC
```

## All Guests
```dataview
TABLE company, role, date
FROM #20vc
WHERE episode_type = "interview"
SORT guest ASC
```

## Market Commentary (The Trio)
```dataview
TABLE date
FROM #20vc
WHERE episode_type = "market_commentary"
SORT date DESC
```
