# 🏆 leaderboard-history/

Archive of every past weekly leaderboard — auto-generated and committed here by the `weekly-leaderboard.yml` GitHub Action.

---

## What's in here

One file per week, named by the date it was generated:

```
leaderboard-history/
├── 2026-08-24.md
├── 2026-08-31.md
├── 2026-09-07.md
└── ...
```

Each file is a snapshot of that week's commit activity across all four Sheba Protocol repos.

---

## File format

```markdown
## Weekly Leaderboard (2026-08-31 to 2026-09-06)

| Rank | Member | Commits | 3+ this week? |
|------|--------|---------|----------------|
| 1    | sira  | 9       | ✅             |
| 2    | tsega | 5       | ✅             |
| 3    | awel | 2       | ❌             |
```

---

## Where this data comes from

- Generated automatically every **Sunday** by the GitHub Action
- Counts commits **org-wide** (across `Daily-Progress-Tracker`, `Write-Up-Activity`, `Project-Activity`, and `CTF-Activity`)
- Also posted as a GitHub Issue the same week — this folder is the permanent, versioned copy

---

## Why keep this history

- Full **year-long** record of team consistency, without needing a spreadsheet
- Easy to compare month-to-month — e.g. `diff` two files, or just scroll
- Useful evidence for mentors, or for each member's own portfolio ("I maintained 3+ commits/week for X months")

---

## ⚠️ Do not manually edit files in this folder

These are auto-generated. If a number looks wrong, fix the workflow (`.github/workflows/weekly-leaderboard.yml`) rather than editing the archived file — otherwise the history stops being trustworthy.
