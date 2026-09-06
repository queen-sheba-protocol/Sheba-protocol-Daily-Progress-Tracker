# 🛡️ Sheba Protocol — Daily Progress Tracker

Central tracker for daily and weekly progress across the **Sheba Protocol** senior security team. This repo is where every member logs what they worked on, what they learned, and what's blocking them — so progress stays visible, consistent, and easy to review over time.

---

## 📌 Purpose

- Track **daily** individual progress across different personal roadmaps (Web AppSec, Network Security, Reverse Engineering, Cloud Security, Active Directory ,etc.)
- Track **weekly** team activity — including commit counts, to see who's staying consistent
- Build a searchable, dated history of the whole team's growth over the year
- Give mentors/leads a fast way to check in without needing a live meeting every day

---

## 📂 Repo Structure

```
Sheba-protocol-Daily-Progress-Tracker/
├── README.md
├── progress/
│   ├── awel/
│   │   ├── 2026-09-01.md
│   │   ├── 2026-09-02.md
│   │   └── ...
│   ├── sirajudin/
│   ├── tsega/
│   └── ... (one folder per member)
├── weekly-summaries/
│   └── 2026-W36.md
├── leaderboard-history/
│   └── 2026-09-07.md
└── .github/
    └── workflows/
        └── weekly-leaderboard.yml
```

---

## 🧾 Daily Log Format

Create one file per day inside your own folder: `Sheba-protocol-Daily-Progress-Tracker/<your-name>/YYYY-MM-DD.md`

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

Commit this daily. One commit = one day logged. No commit = no log for that day.

---

## 📅 Weekly Summary Format

At the end of each week, add a file to `weekly-summaries/YYYY-Www.md` (e.g. `2026-W36.md`):

```markdown
# Week 36, 2026 — Team Summary

**Meetings held this week:** 
**Total commits this week:** 
**Members with 3+ commits:** ✅

## Highlights
- 

## Blockers raised
- 

## Focus for next week
- 
```

---

## 🏆 Automated Weekly Leaderboard

A GitHub Action runs every **Sunday** and automatically:
1. Counts commits per member from the past 7 days across the org
2. Flags anyone with **3+ commits** ✅
3. Posts the results as a new GitHub Issue
4. Archives a dated copy into `leaderboard-history/`

You can also trigger it manually anytime:
**Actions tab → Weekly Commit Leaderboard → Run workflow**

---

## ✅ Contribution Rules

- Log daily in your own folder only — don't edit someone else's log
- Use your GitHub username (or agreed real name) as your folder name, consistently
- Keep entries short and honest — a real blocker is more useful than a padded update
- Weekly summaries are a shared responsibility — whoever leads that week's check-in fills it in i.e team tsega assign for a week meeting control

---

## 👥 Team

Part of the **Sheba Protocol** — a 12-member senior security team pursuing individual roadmaps in web application security, network security, reverse engineering, and Active directory, with shared tracking across four repos:

| Repo | Purpose |
|---|---|
| `Sheba-protocol-Daily-Progress-Tracker` | *(this repo)* Daily/weekly logs and commit tracking |
| `Sheba-protocol-Write-Up-Activity` | Formal CTF and vulnerability writeups |
| `Sheba-protocol-Project-Activity` | Longer-term tools and projects |
| `Sheba-protocol-CTF-Activity` | Live CTF participation logs |

---

## 🔗 Quick Links

- [Weekly Leaderboard Issues](../../issues?q=is%3Aissue+label%3Aweekly-report)
- [All Progress Logs](./)
- [Weekly Summaries](./weekly-summaries)
