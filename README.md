# BYO-tooling — Build Your Own Custom Fit Tools

Instead of adopting someone else's AI workflow, build your own custom fit workflow that suits you uniquely.  Borrowing someone else's framework, skill pack, or agent fleet works until it doesn't.  When you know why each part of the tooling is made, you build a deeper intuition as well as a bespoke tool to amplify your specific abilities. 

This tool is meant to build slow and steady momentum. You build your own workflow **one small piece at a time**, and every piece records the assumption behind it — what you believed, why, and what would prove it wrong. When something annoys you later, you look up the assumption, change your mind *on the record*, and rebuild. You end up with tooling you understand completely, because you grew it.

The rules that make this work are seven short immutables in [`AGENTS.md`](./AGENTS.md). Everything else — folder names, how often you build, how your agent talks to you — is yours to discover. Nothing here is anyone's workflow but yours.

## Get started (one step)

Copy this prompt into your AI tool of choice — Claude Code, Cursor, or any coding agent — and press enter:

```text
Get me set up with BYO-tooling: copy https://github.com/Worley/byo-tooling into a
new folder of my own (git clone it, or download and unzip its ZIP — whichever works
here), then read its AGENTS.md and start exercise 000.
```

That's the whole setup. Your agent fetches the folder, reads the rules, and interviews you for a few minutes about how you like to work — stop whenever you want, it resumes later. It writes down your first assumptions and suggests your first build. If you'd like the folder version-controlled, just tell your agent "set up git here" — it'll handle it.

## What's inside

- **[`AGENTS.md`](./AGENTS.md)** — the seven rules, readable in two minutes
- **[`assumptions.md`](./assumptions.md)** — your ledger of what you believe and why (starts empty)
- **[`exercises/`](./exercises/)** — one short log per thing you build
- **[`elements/`](./elements/)** — the things you build (starts empty, on purpose)
- **Three starter skills**, all freely editable: the [interview](./skills/tooling-tutorial/SKILL.md), a [survey helper](./skills/tooling-survey/SKILL.md) that knows what's already out there, and a [voice tuner](./skills/register-tuning/SKILL.md) (plain-language → expert-terse → caveman)
- **[`awesome-tooling.md`](./awesome-tooling.md)** — a verified map of open-source tools, so you compare before you build

## Where this comes from

A conviction that **the best way to learn AI is to just do it.** The pieces of tooling worth trusting are always the ones cultivated directly. You don't need to adopt a single tooling process for your team or org, bring your own amplification suite and prove how it can contribute better

Conventions and mechanics borrowed from the open-source world are cited inside the specific files that use them — see each skill's Sources section, and [`awesome-tooling.md`](./awesome-tooling.md) for the wider map. [MIT license](./LICENSE) — do anything you want with it.
