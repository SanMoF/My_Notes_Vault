---
tags: [dashboard, MOC]
---

# 🧠 Mechatronics Second Brain

Welcome to your second brain! This vault is organized using the PARA method adapted for engineering students.

## 🚀 Quick Access

### Active Projects
```dataview
table status, date_started as "Started"
from "20_Projects"
where status = "Active"
sort date_started desc
```

### Current Courses
```dataview
table professor, semester
from "10_Courses/Active"
sort semester desc
```

### Today's Tasks
- [ ] Check [[Daily_Note]]
- [ ] Review active projects
- [ ] Capture new ideas to [[00_Inbox]]

## 📁 Vault Structure

| Folder | Purpose |
|--------|---------|
| [[00_Inbox]] | Quick capture - empty your brain here |
| [[10_Courses]] | All academic content |
| [[20_Projects]] | Hands-on builds and projects |
| [[30_Knowledge]] | Evergreen technical notes |
| [[40_Resources]] | References and materials |
| [[50_Career]] | Professional development |
| [[60_Daily]] | Journals and daily notes |
| [[99_Meta]] | Templates and system files |

## 🗺️ Maps of Content
- [[Mechatronics MOC]] - Core knowledge areas
- [[Components MOC]] - Parts catalog
- [[Programming MOC]] - Code references
- [[Career MOC]] - Career roadmap

## 📝 Recently Modified
```dataview
list
file.mtime
sort file.mtime desc
limit 10
```

## 🎯 Semester Goals
- [ ]

---
*Last updated: {{date:YYYY-MM-DD}}*
