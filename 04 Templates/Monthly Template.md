---
tags: monthly-note
month: <% tp.date.now("MM", 0, tp.file.title, "YYYY - MM-MMMM") %>-<% tp.date.now("MMM", 0, tp.file.title, "YYYY - MM-MMMM") %>
year: <% tp.date.now("YYYY", 0, tp.file.title, "YYYY - MM-MMMM") %>
banner: https://preview.redd.it/arqa352ph7x61.jpg?width=960&crop=smart&auto=webp&s=84f9245d607b029667d5bfc4abf36547fc6213de
---
⠀
###### [[<% tp.date.now("YYYY - MM-MMMM", "P-1M", tp.file.title, "YYYY - MM-MMMM") %>|↶ PREVIOUS WEEK]] ⁝ [[<% tp.date.now("YYYY - MM-MMMM", P1M, tp.file.title, "YYYY - MM-MMMM") %>|FOLLOWING WEEK ↷]]
# ◌ <% tp.file.title %>

## Weeks
```dataview
TABLE
month as "Month"
FROM "03 Periodic/02 Weekly"
WHERE month = "<% tp.file.title %>"
```

## Days
```dataview
TABLE
month as "Month"
FROM "03 Periodic/01 Daily"
WHERE month = "<% tp.file.title %>"
```
