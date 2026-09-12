# Geopolitics Brief Prompt Pack Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build a ready-to-run Codex prompt pack for a multi-agent daily geopolitics research desk.

**Architecture:** Three scout roles produce independent discovery artifacts. Verification, analysis, red-team review, and editing then run sequentially. The dated brief is canonical, with `briefs/latest.md` and root `TODAY.md` as convenience copies.

**Tech Stack:** Markdown, Codex repository instructions (`AGENTS.md`), live web research at runtime.

**Spec:** `docs/superpowers/specs/2026-09-07-geopolitics-brief-design.md`

## Global Constraints

- The daily brief must use live web research.
- The canonical output is `briefs/YYYY-MM-DD/daily-brief.md`.
- The workflow must preserve intermediate scout, verification, analysis, and red-team artifacts.
- `briefs/latest.md` and `TODAY.md` must be byte-identical convenience copies of the canonical brief.
- Version 0 does not implement scheduling, Obsidian integration, databases, or regional specialist agents.

---

### Task 1: Repository operating instructions and editorial policy

**Files:**
- Create: `AGENTS.md`
- Create: `config/priorities.md`
- Create: `config/source-policy.md`

**Interfaces:**
- Consumes: user-approved functional research-desk architecture.
- Produces: shared orchestration, ranking, and verification rules used by every role.

- [x] **Step 1:** Write root instructions that define the artifact flow and stable convenience-copy behavior.
- [x] **Step 2:** Write significance scoring and anti-noise rules.
- [x] **Step 3:** Write source hierarchy, independence, conflict-claim, and verification rules.
- [x] **Step 4:** Check that all three files agree on scope and terminology.

### Task 2: Specialized role prompts

**Files:**
- Create: `agents/news-scout.md`
- Create: `agents/deep-scout.md`
- Create: `agents/claim-scout.md`
- Create: `agents/source-auditor.md`
- Create: `agents/analyst.md`
- Create: `agents/red-team.md`
- Create: `agents/editor.md`

**Interfaces:**
- Consumes: shared policy files from Task 1.
- Produces: role-specific Markdown artifacts at the exact paths defined by `AGENTS.md`.

- [x] **Step 1:** Define complementary scout responsibilities and structured outputs.
- [x] **Step 2:** Make the Source Auditor the factual choke point and require source inspection.
- [x] **Step 3:** Restrict the Analyst to verified factual inputs.
- [x] **Step 4:** Require adversarial red-team findings with severity and editorial actions.
- [x] **Step 5:** Require the Editor to apply valid criticism and create all final copies.

### Task 3: Final format and first-run entry point

**Files:**
- Create: `templates/daily-brief.md`
- Create: `KICKOFF.md`
- Create: `README.md`

**Interfaces:**
- Consumes: workflow and role prompts.
- Produces: a copy-pasteable first-run task and a fixed final brief schema.

- [x] **Step 1:** Define the final Markdown structure.
- [x] **Step 2:** Create a kickoff prompt that instructs Codex to execute the full workflow without routine clarification.
- [x] **Step 3:** Document the expected output tree and first-run procedure.

### Task 4: Verification and packaging

**Files:**
- Verify: all files above.
- Create package externally after verification.

**Interfaces:**
- Consumes: completed prompt pack.
- Produces: a portable repository archive ready for the user to open in Codex.

- [x] **Step 1:** Verify every path referenced by `AGENTS.md` exists.
- [x] **Step 2:** Scan active prompt/config files for placeholder markers such as `TBD` and unfinished instructions.
- [x] **Step 3:** Verify the role output paths form a complete pipeline with no conflicting writers.
- [x] **Step 4:** Commit the prompt pack in the fresh repository.
- [x] **Step 5:** Create a ZIP archive for handoff.
