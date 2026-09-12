# Mouton Geopolitics Research Desk

## Mission

Produce a daily, source-grounded geopolitics brief for MrMouton / Anything Else.
The product is stream preparation, not a generic news digest.

The desk should answer:

1. What materially changed in the last ~30 hours?
2. Why does it matter strategically?
3. Which facts or narratives remain disputed?
4. What should we watch next?
5. Which issues are especially useful for live discussion?

## Repository map

Read these before running the desk:

- `config/priorities.md`: significance and ranking rules.
- `config/source-policy.md`: sourcing, verification, and uncertainty rules.
- `templates/daily-brief.md`: required final format.
- `agents/*.md`: role instructions for each research desk agent.

## Daily workflow

For a run dated `YYYY-MM-DD`:

1. Establish the actual current time and timezone. Default to `America/New_York` unless the kickoff prompt specifies otherwise.
2. Use a research window of approximately the previous 30 hours. Include older material only when needed to explain a newly changed situation.
3. Create `briefs/YYYY-MM-DD/research/`.
4. Delegate these three roles in parallel when collaboration/subagent tools are available:
   - `agents/news-scout.md` -> `briefs/YYYY-MM-DD/research/news-scout.md`
   - `agents/deep-scout.md` -> `briefs/YYYY-MM-DD/research/deep-scout.md`
   - `agents/claim-scout.md` -> `briefs/YYYY-MM-DD/research/claim-scout.md`
5. Run `agents/source-auditor.md` over all scout files. It may and usually should perform additional web research. Write `briefs/YYYY-MM-DD/verified.md`.
6. Run `agents/analyst.md` using `verified.md` plus the scout files. Write `briefs/YYYY-MM-DD/analysis.md`.
7. Run `agents/red-team.md` using `verified.md` and `analysis.md`. Write `briefs/YYYY-MM-DD/red-team.md`.
8. Run `agents/editor.md` using all upstream artifacts. Write `briefs/YYYY-MM-DD/daily-brief.md`.
9. Copy the finished brief byte-for-byte to:
   - `briefs/latest.md`
   - `TODAY.md`

`briefs/YYYY-MM-DD/daily-brief.md` is canonical. `briefs/latest.md` and root-level `TODAY.md` are convenience copies and must not be edited independently.

## Delegation rules

If collaboration tools are available, parallelize independent research. Do not have multiple agents edit the same file.

If collaboration tools are unavailable, perform the same roles sequentially in the root agent. Keep the intermediate files. Do not collapse the workflow into one opaque pass.

Messages sent between agents must be legible to a human reviewer.

## Current-information requirement

A daily run requires live web access. Never fabricate a current brief from model memory.

If a particular source is inaccessible, use other credible sources and note the limitation. If current web research is broadly unavailable, stop the daily run and explain the blocker rather than producing a fake current brief.

## Evidence rules

- Every material factual claim in the final brief must be traceable to a source inspected during this run.
- Search snippets, AI summaries, and aggregator blurbs are discovery aids, not evidence.
- Distinguish independent confirmation from multiple outlets repeating the same underlying claim.
- Distinguish FACT, CLAIM, ASSESSMENT, and SPECULATION internally. The final prose can be natural, but uncertainty must remain visible.
- Do not treat an official statement as independently verified merely because it is official.
- Do not manufacture balance when evidence is lopsided.
- Prefer exact dates and concrete quantities when material.
- Correctness beats speed. Significance beats volume.

## Scope rules

Do not force regional quotas. A quiet region can be absent.

Prioritize wars, escalation, deterrence, diplomacy, elections with geopolitical consequences, sanctions, strategic trade, energy security, nuclear issues, alliance behavior, coups/regime instability, major international legal developments, and changes in US foreign policy.

Exclude routine diplomatic boilerplate, repetitive battlefield updates with no strategic consequence, celebrity/personal drama, and stories that are merely sensational.

## Final-product constraints

- Target 5-8 major developments.
- Maximum 8 Rapid Fire items.
- Target roughly 10-15 minutes of reading.
- Use direct hyperlinks to useful sources.
- Give exact research cutoff time near the top.
- If the day is quiet, make the brief shorter.
- If one event dominates the day, give it proportionally more space.
- Never pad to hit a story count.

## Historical continuity

When prior briefs exist, inspect at least `briefs/latest.md` before research if it is from an earlier date. Use it only to identify continuing threads and changed assessments. Re-verify current facts in the new run.

Do not allow yesterday's wording to become today's evidence.
