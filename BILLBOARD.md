# Billboard

Shared state for KC's agent roster. Read your department's section before
starting work; append a dated entry when you finish a unit of work. See
[CLAUDE.md](CLAUDE.md) for the protocol. `ceo` owns cleanup of this file.

## Pending Approval

Work that is drafted and review-passed, waiting on Ben's quality check
before it executes (ships, publishes, deploys, sends, merges). Nothing
leaves this section except by Ben's explicit go-ahead, logged in Decisions
log below.

(nothing pending)

## Decisions log

- 2026-06-25 — Stood up the agent roster (ceo, hermes, code-gen, code-review,
  editor, artist) and this billboard protocol. No product direction chosen
  yet — that's the next decision for Ben (Chairman).
- 2026-06-25 — Added a Pending Approval gate: `ceo` bundles finished,
  review-passed work there; nothing executes until Ben approves it.
- 2026-06-25 — Wired the roster up as real Claude Code subagents
  (`.claude/agents/hermes.md`, `code-gen.md`, `code-review.md`, `editor.md`,
  `artist.md`); `ceo` is the top-level session itself. Roster is now
  operable, still pre-product.

## CEO / Hermes

(open items, scheduling, cross-department blockers go here)

## Vibecoding Dept (code-gen / code-review)

(no project yet)

## Content Dept (editor / artist)

(no project yet)
