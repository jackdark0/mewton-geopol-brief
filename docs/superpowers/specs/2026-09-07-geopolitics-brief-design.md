# Geopolitics Brief Research Desk Design

## Goal

Create a Codex-friendly multi-agent research desk that produces one inspectable, source-grounded daily geopolitics brief in Markdown.

## Architecture

Three independent scouts perform broad news discovery, under-covered strategic discovery, and contested-claim discovery. A Source Auditor deduplicates and verifies their findings. An Analyst interprets only verified evidence. A Red Team challenges the analysis. An Editor produces the final brief and convenience copies.

## Data flow

```text
News Scout ─┐
Deep Scout ─┼─> Source Auditor -> Analyst -> Red Team -> Editor -> dated brief
Claim Scout ┘                                                    ├-> briefs/latest.md
                                                                 └-> TODAY.md
```

## Canonical artifact

`briefs/YYYY-MM-DD/daily-brief.md` is the canonical daily brief.

`briefs/latest.md` and root-level `TODAY.md` are exact convenience copies. This gives the user a stable, obvious path without sacrificing archival organization.

## Scope

Version 0 includes only the prompt pack, source/ranking policy, output template, repository instructions, and kickoff prompt.

It deliberately excludes scheduling, Obsidian syncing, databases, persistent actor dossiers, regional specialist agents, and feedback learning.

## Success criteria

A Codex agent with live web access can open the repo, receive `KICKOFF.md`, follow the role prompts, preserve intermediate artifacts, and produce a dated brief plus the two stable convenience copies.
