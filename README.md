# Tasks

A minimalist, mobile-first task tracker and gamified rewards system built as a self-contained, single-file web app.

Zero build steps. Zero backend. 100% front-end persistence.

---

## Features

- **Task Management:** Organizable with UUIDs, priorities (`P1`, `P2`, `P3`), due dates, editable details, and Notion-style colored tags (`Work`, `Personal`, `Finance`, `Health`, `Learning`).
- **Gamified Points System:** Earn completion points on check-off; points are deducted if unchecked. Adjusting points on completed tasks automatically balances your ledger.
- **Filters & Sorting:** Quick-filter by *Inbox*, *Due Today*, *Past Due*, *Completed*, or 1-by-1 label. Sort by *Priority*, *Due Date*, or *Points*.
- **Rewards Catalog:** Add custom rewards with point costs. Each reward features an interactive progress bar and automatic disabled states until you earn enough points.
- **Mobile & Click Ergonomics:** Floating Action Button (FAB), pre-filled input memory, and a global `N` keyboard shortcut to open the task creator with zero wasted clicks.
- **Local Persistence:** All data is saved directly in browser `localStorage`.

---

## Tech Stack

- **HTML5 & Vanilla JavaScript** (Single-file SPA architecture)
- **Tailwind CSS** (CDN)
- **Lucide Icons** (CDN)

---
