---
tags: [meta, zettelkasten, guide]
---

# Zettelkasten Workflow

A Zettelkasten (German for "slip box") is a note-taking system for building a web of connected knowledge.

## The Four Types of Notes

### 1. Fleeting Notes
- **Purpose:** Capture ideas quickly before you forget
- **Lifespan:** Temporary - process within 1-2 days
- **Template:** [[Fleeting_Note]]
- **Storage:** 00_Inbox

### 2. Literature Notes
- **Purpose:** Capture what a source says
- **Rules:**
  - Be selective - don't highlight everything
  - Write in your own words
  - Include exact quotes with page numbers
  - One source can generate multiple literature notes
- **Template:** [[Literature_Note]]
- **Storage:** 40_Resources/Literature_Notes

### 3. Permanent Notes
- **Purpose:** Your own ideas, insights, arguments
- **Rules:**
  - One idea per note
  - Written for your future self (future-proof)
  - Include sources but write in your own words
  - Make connections to existing notes
  - Use the UID (YYYYMMDD + time) for unique ID
- **Template:** [[Permanent_Note]]
- **Storage:** 30_Knowledge/ or topic folders

### 4. Index Notes (MOCs)
- **Purpose:** Entry points and navigation
- **Rules:**
  - Don't duplicate content
  - Link to permanent notes
  - Group by topic/project
- **Template:** [[Index_Note]]
- **Storage:** 30_Knowledge/

## The Workflow

```
Fleeting Note (capture)
    ↓
Literature Note (understand source)
    ↓
Permanent Note (your insight)
    ↓
Index Note (organize)
```

## Key Principles

1. **Atomic Notes** - One idea per note
2. **Own Words** - Don't copy-paste; understand and rewrite
3. **Connect** - Always link to related notes
4. **No Folders** - Use links and tags instead of rigid hierarchies
5. **Numbering** - Use UID format: `YYYYMMDDHHmm`

## Example Workflow

1. **Read** a paper on PID control
2. **Create** [[Source_Reference]] for the paper
3. **Write** [[Literature_Note]] for key concepts
4. **Develop** [[Permanent_Note]] on "PID Tuning for Nonlinear Systems"
5. **Connect** to existing [[Control Systems MOC]]
6. **Link** from [[Mechatronics MOC]]

## Fleeting vs Permanent

| Fleeting | Permanent |
|----------|-----------|
| Quick capture | Refined thought |
| Temporary | Permanent |
| Raw | Polished |
| Many per day | Few per day |
| Inbox folder | Knowledge folders |

---

*For a deep dive, read "How to Take Smart Notes" by Sönke Ahrens*
