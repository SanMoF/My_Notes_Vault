---
tags: [dashboard]
---

# Mechatronics Vault

Your notes for courses and projects.

## Quick Links
- [[00_Inbox]] - Quick notes to organize later
- [[10_Courses/Active]] - Current classes
- [[20_Projects/Active]] - What you're building now

## Templates
- **New Course:** [[Course_Note]]
- **New Project:** [[Project]]
- **Quick Reference:** [[Formula_Sheet]]

## Current Courses
```dataview
table professor, semester
from "10_Courses/Active"
```

## Active Projects
```dataview
table status, date_started as "Started"
from "20_Projects/Active"
sort date_started desc
```

---
*Open [[99_Meta/Quick_Start]] to learn the simple workflow*
