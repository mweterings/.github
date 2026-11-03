<!--
One-minute briefing for a reviewer who has the diff, not a lab notebook.
Short, simple sentences. Drop any section with nothing to say (except Scope).
This body becomes the squash commit body: keep it under about 40 lines.
No full SHAs, file-by-file checklists or "CLEAN" verdicts.
-->

## Why

<!-- The problem and the approach, in 1-3 sentences. -->

## What changed

<!-- 1-3 bullets. Name a symbol or path only when it carries the change. -->

## Scope

<!-- Always. What this covers and what it deliberately leaves out (follow-ups, known gaps). -->

## Tradeoffs

<!-- Only rejected alternatives a reviewer would ask about. Delete if there was no real choice. -->

## Blast Radius

<!-- 1-2 sentences: who or what this touches and why that is safe or risky. -->

## Verification

<!-- 1-3 bullets, each a real command, CI job or manual check and its outcome.
Perf: one number, before -> after. Screenshots or video below only when they prove a claim. -->

## Review

**Door:** `two-way` | `one-way`
<!-- two-way = cheap to undo. one-way = schema, stored data, public contracts, deletions, secrets. -->

**Carve-out:** `yes` | `no`
<!-- Yes when it changes agent instructions (AGENTS.md, .cursor/), CI (.github/), package.json
scripts or dependencies, the lockfile, lint/TS/test/build config, Docker or deploy config,
secrets/env, or the review/merge process. Yes means Michael approves. Reviewer assigns the risk grade. -->

**Cleanup:** `none` | `needed` | `done`
<!-- Leftovers from this change, and what to delete later. -->

**Refs:** <!-- Closes #123 / Refs #456 -->
