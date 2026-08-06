---
name: tooling-tutorial
description: Run or resume Exercise 000 - the assumptions interview that seeds the owner's workflow preferences. Use when the owner starts this repo fresh, says "start", "tutorial", or "exercise 000", when they want to resume or revisit probing, or when a logged failure lands in a preference domain that was never probed.
---

Interview the owner to surface their workflow preferences as falsifiable assumptions (see `AGENTS.md` → Formats). This skill is **predefined but freely modifiable** — it is a default, not kernel. If the owner edits the question style, round size, or domains, that's the system working; suggest they log the edit as an assumption about how they like to be asked.

## First: choose the entry mode

Before any question, scan for prior art: existing agent-instruction files (CLAUDE.md, AGENTS.md, cursor rules), READMEs, ADRs, config files, notes — in this repo and anywhere the owner points you.

- **Nothing meaningful found → greenfield mode**: probe from scratch (below).
- **Existing decisions found → brownfield mode**: excavate first, probe the gaps second. Someone with written decisions has already made choices — raw probing would ignore their history and feel like a form.

## Brownfield: excavate before you probe

1. Read what exists and extract **candidate assumptions** — every rule, convention, or repeated pattern in their docs is a preference somebody once had. Quote the source.
2. Present candidates in small batches for triage: *"Your notes say ⟨X⟩ — is this still you?"* Each becomes:
   - **asserted** — "yes, and here's why" (capture the why)
   - **adopted-untested** — "it's there but I never really chose it"
   - **superseded/dead** — "not anymore" (record what replaced it, if anything)
3. Only then run probing rounds — starting with the domains their documents *never mention*, which are usually the interesting ones.

## Probing: frontier rounds, endlessly

Work like a design tree. Seed domains (a starting map, not a ceiling):

1. How you work today — current loop, where time goes, what friction brought you to AI
2. Trust and control — what the agent may do unasked; what's irreversible *to you*
3. Reviewing work — diffs vs prose vs demos; how much explanation
4. What "done" means — what evidence convinces you
5. Communication — interruptions, question format, verbosity, and **register** (how technical the agent's language should be — see the `register-tuning` skill for presets to try)
6. Knowledge placement — what gets written down, and where
7. Failure ritual — what happens when the agent annoys you
8. **First project** (contextual — fires when the owner starts real work with their tooling, per kernel immutable 7): how do projects consume the tooling — copy (fails by drift), reference (fails by coupling), or fork (fails by divergence)? Present each option *with its characteristic failure mode named*, so the assumption's falsified-when clause is pre-written. Where do project-specific deviations live, and what promotes one to the tooling repo (a good default: appearing independently in two projects)? Should this repo keep a `projects.md` pointer index of its consumers — pointers only, never content?

**Rounds are small: 2–3 questions, answerable in one breath.** Number each question and follow it with a recommended answer — but **recommend on decisions, never on self-reports**: questions about *their* life and history get no recommendation, only an example of what an answer sounds like.

**The frontier is recomputed after every round.** New questions come from four places — this is what makes probing endless rather than a fixed script:

- **Tensions** between answers ("you want speed *and* approval on every edit — where's the line?")
- **Specifics mentioned but unexplored** (they said "wasted an afternoon" — on what, and what would have caught it sooner?)
- **Domains untouched** — seed domains never visited, or new domains their answers imply
- **Aging adopted-untested entries** — defaults accepted long ago and never tested by events

## Hard cases: when there's nothing to go on

Some owners answer "I don't know" to everything — overwhelmed by the whole topic, or skeptical and half-hoping to prove this doesn't work. The tutorial's job is to be **ruthlessly supportive**: never make them feel quizzed, never stall, and find preferences by other roads when asking doesn't work.

- **The two-IDK rule.** After two uninformative answers in a domain, never ask a third abstract question. Switch roads (below) or mark the domain *unexplored* and move on — an unexplored domain is a finding, not a failure, and its probe returns later when a real event earns it.
- **Road 1 — episodic anchoring.** Never ask people to characterize themselves ("how do you like to review work?") after an IDK; ask what happened *last time* ("the last thing you fixed — did you read the whole diff or just run it?"). Episodic memory answers when self-knowledge can't.
- **Road 2 — show, don't ask.** Do a tiny real task two ways and ask which annoyed them less. A preference revealed by reaction is worth more than one claimed in the abstract — record it as **asserted** (they reacted; that's real evidence).
- **Road 3 — artifact excavation.** Ask for a thing, not an opinion: a folder listing, the last document they wrote, a script they use. Derive probes from what's actually there — this turns a greenfield interview into a brownfield one, and artifacts never say "I don't know."
- **Co-opt the skeptic.** "This AI stuff won't work for me" is not resistance — it's the first falsifiable assumption. Write it down as A-001, origin **asserted**, and design its falsified-when clause *with them* ("what's the smallest thing that would have to work for you to soften this?"). Their urge to prove failure becomes the engine of the experiment.
- **Default-with-veto fast path.** For the overwhelmed, offer: "want me to pick sensible defaults for everything, and we fix them as they annoy you?" Legitimate path — every entry tagged **adopted-untested**, the failure ritual becomes the primary discovery channel, and the ledger says so honestly.
- **First win inside ten minutes.** If two rounds stall, stop interviewing. Build something tiny from *any* detected friction — even a guessed one — and let them react to it. The tutorial's success metric is a felt win, not a completed questionnaire.
- **Tone floor:** never re-ask a dodged question in the same words; make progress visible ("two assumptions recorded — that's already enough to start"); "I don't know" gets written down as an open domain, never treated as a wrong answer.

## Recording

- Echo each assumption back **in full** — statement, origin tag, falsified-when — before writing it to `assumptions.md`. The format teaches by exposure.
- The **first** adopted-untested entry gets the explicit callout: "you accepted my default, so this is tagged adopted-untested — when something annoys you, this is the first suspect." Say it once, early; don't repeat it every time.
- Answers about current frictions seed the owner's **starter backlog** — record candidate exercises in the Exercise 000 log.

## Stopping and resuming

- The owner can say "enough" at any point. Log it as an assumption (how they prefer to be probed), update the round state in `exercises/000-first-assumptions.md`, and give a **READY verdict**: assumptions count, adopted-untested count, starter-backlog candidates, and what remains probable.
- Tutorial mode off ≠ over. Offer **contextual re-entry**: when a logged failure lands in a domain never probed (or falsifies an aging adopted-untested entry), offer that round then — hand-holding returns when it's earned, never before.

## Sources

- [mattpocock/skills](https://github.com/mattpocock/skills) `grilling` (MIT) — the design-tree/frontier-round interview mechanic this adapts.
- [Architecture Decision Records](https://adr.github.io/) — supersession over rewriting; brownfield excavation treats existing docs as undocumented ADRs.
- Staged-bootstrap-with-artifacts and questionnaire-with-defaults patterns — as seen in [github/spec-kit](https://github.com/github/spec-kit) (MIT) and agent-project bootstrap flows ([Claude Code memory/init docs](https://code.claude.com/docs/en/memory)).
