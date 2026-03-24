# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is an **Obsidian Vault** for Mechatronics engineering coursework and projects. It uses Git for version control via the obsidian-git plugin.

## Architecture & Structure

### Folder Organization (PARA-based)

```
My_Vault/
├── 00_Inbox/          ← Temporary notes to process
├── 10_Courses/        ← Course notes organized by code
│   ├── Active/        ← Current semester courses
│   ├── Completed/     ← Finished courses
│   └── Reference/     ← Reference materials
├── 20_Projects/       ← Hands-on projects
│   ├── Active/        ← Current builds
│   └── Completed/     ← Finished projects
├── 30_Knowledge/      ← MOCs and reference knowledge
├── 40_Resources/      ← External resources (PDFs, papers)
└── 99_Meta/           ← Templates and system config
    └── Templates/     ← Note templates
```

### Key Files

- **Dashboard.md** - Main hub with course dashboard and quick links
- **30_Knowledge/Mechatronics MOC.md** - Map of Content for mechatronics topics

### Templates System (`99_Meta/Templates/`)

| Template | Purpose |
|----------|---------|
| `Course_Note.md` | New course container with metadata |
| `Lecture Notes.md` | Individual lecture note structure |
| `Project.md` | Project tracking with mechanical/electrical/code sections |
| `Formula_Sheet.md` | Quick reference formulas |

## Version Control

- **Plugin**: obsidian-git v2.38.0 (Vinzent)
- **Auto-backup**: Enabled via plugin
- **Commit pattern**: Daily vault backups with timestamps
- **Branch**: main

## Active Plugins

### Community Plugins
- **obsidian-git** - Git integration
- **quickadd** - Quick capture automation

### Core Plugins Enabled
templates, daily-notes, note-composer, command-palette, backlink, graph, canvas, tag-pane, outline, word-count, file-recovery, sync, bases

## Note Conventions

### Naming
- Courses: `Course Name` (e.g., `Control`)
- Projects: `Project - Name`
- Daily notes: `YYYY-MM-DD.md`

### Frontmatter Patterns
- Courses: `course`, `code`, `semester`, `professor`, `date_created`
- Projects: `project`, `status`, `date_started`
- Tags: Use `[[wikilinks]]` for connections

### Workflow
1. Class notes → `10_Courses/Active/[Course]/`
2. Ideas → `00_Inbox/`
3. Projects → `20_Projects/Active/` with Project template
4. Weekly: Process Inbox, archive completed items

## Current Context

### Active Courses (6)
(Control), (Kinematics), (Process Simulate), (Industrial Networks), (CNC), (Computer Vision)

### Knowledge Domains
Control Systems, Programming (C++/Python/MATLAB/ROS), Mechanical (CAD/Manufacturing), Electrical (Circuits/Electronics/Signal Processing)
