# Mouton Geopolitics Research Desk

A small multi-agent research workflow for producing a daily geopolitics brief in Markdown.

## First run in Codex

1. Open this repository as the Codex project.
2. Make sure the agent has live web access.
3. Paste the contents of `KICKOFF.md` as the task.
4. Let Codex follow `AGENTS.md` and retain the intermediate artifacts.
5. Review `TODAY.md` first. The archived canonical copy lives at `briefs/YYYY-MM-DD/daily-brief.md`.

Codex supports repository-level `AGENTS.md` instructions, so the root file is deliberately short enough to act as a map into the more specialized prompt files.

## Output tree after a successful run

```text
briefs/
├── latest.md
└── YYYY-MM-DD/
    ├── research/
    │   ├── news-scout.md
    │   ├── deep-scout.md
    │   └── claim-scout.md
    ├── verified.md
    ├── analysis.md
    ├── red-team.md
    └── daily-brief.md

TODAY.md
```

## Design principle

The scouts discover independently. The source auditor reconciles and verifies. The analyst interprets. The red team attacks the interpretation. The editor gets the last word.

This keeps sourcing separate from analysis and makes failures inspectable instead of hiding them inside one enormous prompt.
