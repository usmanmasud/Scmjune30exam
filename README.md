# Git & GitHub — SWE4201 Assignment

**Course:** SWE4201 — Software Configuration Management & Maintenance  
**Institution:** Bayero University Kano  
**Student:** Usman Masud Aliyu  
**Reg No:** CST/22/SWE/00834  

---

## Overview

This project is a simple static website that explains the fundamentals of **Git** and **GitHub** as part of the SWE4201 course on Software Configuration Management and Maintenance. It covers key concepts, essential commands, and the difference between Git (the tool) and GitHub (the platform).

---

## Files

| File | Description |
|------|-------------|
| `index.html` | Main webpage with all content sections |
| `style.css` | Stylesheet for layout, colours, and typography |
| `README.md` | This file — project documentation |

---

## Topics Covered

1. **What is Git?** — Definition and background of the distributed version control system
2. **Core Git Concepts** — Repository, Commit, Branch, Merge, Staging Area, Clone
3. **Essential Git Commands** — A reference table of the most-used commands
4. **What is GitHub?** — Overview of the cloud collaboration platform
5. **Git vs GitHub** — A comparison table of the two
6. **A Typical Git Workflow** — Step-by-step guide from init to merge

---

## How to View

Since this is a plain static site, no server or build step is needed.

1. Download or clone this project folder.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, etc.).
3. The page will load with `style.css` applied automatically.

---

## Key Git Concepts (Quick Reference)

### What is Version Control?
Version control is a system that records changes to files over time so you can recall specific versions later. Git is the most widely used version control system in the world.

### Three States of Git
- **Working Directory** — Where you edit files.
- **Staging Area (Index)** — Where you prepare changes before committing.
- **Repository (.git/)** — Where Git permanently stores committed snapshots.

### Common Git Commands
```bash
git init                  # Initialise a repository
git clone <url>           # Clone a remote repo
git add <file>            # Stage a file
git commit -m "message"   # Commit staged changes
git status                # Check current state
git log                   # View commit history
git branch <name>         # Create a branch
git checkout <branch>     # Switch branch
git merge <branch>        # Merge a branch
git push                  # Upload commits to remote
git pull                  # Fetch and merge remote changes
```

### Git vs GitHub

| | Git | GitHub |
|--|-----|--------|
| Type | CLI Tool | Cloud Platform |
| Purpose | Local version control | Remote hosting & collaboration |
| Needs internet | No | Yes |
| Made by | Linus Torvalds (2005) | GitHub Inc. (2008) |

---

## Technologies Used

- HTML5
- CSS3 (no frameworks — plain CSS)

---

*Submitted in partial fulfilment of the requirements for SWE4201 at Bayero University Kano.*
