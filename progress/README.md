# 📁 progress/

This folder holds every member's **daily log**, organized into one subfolder per person.

---

## Structure

```
progress/
├── Awel Abduljelil/
│   ├── 2026-09-01.md
│   ├── 2026-09-02.md
│   └── ...
├── Sirajuddin-Seid/
│   ├── 2026-09-01.md
│   └── ...
└── <your-name>/
    └── YYYY-MM-DD.md
```

- **One folder per member** — named consistently with your GitHub username or agreed real name
- **One file per day** — named `YYYY-MM-DD.md` (e.g. `2026-09-06.md`)
- Only edit files inside **your own** folder

---

## How to add today's log

1. Find (or create, if it's your first day) your folder: `progress/<your-name>/`
2. Create a new file named with today's date: `YYYY-MM-DD.md`
3. Copy this template into it:

```markdown
# YYYY-MM-DD — <Your Name>

**Roadmap track:** Web AppSec / Network Security / Reverse Engineering / Cloud Security

**What I did today:**
- 
- 

**What I learned:**
- 

**Blockers:**
- 

**Plan for tomorrow:**
- 
```

4. Fill it in and commit:

```bash
git add progress/<your-name>/YYYY-MM-DD.md
git commit -m "Daily log: <your-name> YYYY-MM-DD"
git push
```

---

## Why this matters

- Each commit here counts toward your **weekly commit total**, tracked automatically every Sunday
- 3+ commits in a week = flagged ✅ on the team leaderboard
- A full year of dated logs builds a real record of your growth — useful for your own portfolio, mentors reviewing progress, or looking back on how far you've come

---

## Rules

- Don't skip the date in the filename — the leaderboard script and any future search tooling rely on consistent naming
- Don't edit or delete another member's log files
- Keep entries honest and specific — vague entries ("worked on stuff") aren't useful to you or your mentors later
- If you miss a day, don't backdate it — just note it in the next day's log instead