---
name: register-tuning
description: Use when the owner wants the agent to talk differently - more technical, less technical, terser, plainer, or a persona - or when their reactions suggest the current register isn't landing (glazed-over replies to jargon, impatience with over-explanation). Tunes the conversational register and records it as an assumption.
---

A default, not kernel — edit freely. The register the agent speaks in is a workflow preference like any other: discoverable, recordable, falsifiable.

## Tuning

1. **Diagnose before prescribing.** Ask what's not landing: too much jargon? too much hand-holding? too many words? Or probe with a sample — render the same answer two ways and ask which reads better.
2. **Offer the preset ladder**, low to high ceremony:
   - **plain-language** — no unexplained jargon; every technical term gets a one-phrase gloss the first time
   - **standard** — normal technical conversation, terms used freely, explanations on request
   - **expert-terse** — assume expertise, cut preamble, lead with the diff/command/number
   - **caveman** — few words. why use many token when few token do trick. Silly and genuinely useful: strips filler so hard that ~40–65% of output tokens disappear while the content stays ([JuliusBrussee/caveman](https://github.com/juliusbrussee/caveman), [carlosduplar/caveman-output-style-claude-code](https://github.com/carlosduplar/caveman-output-style-claude-code))
3. **Record it as an assumption** (asserted if they chose, adopted-untested if they took your suggestion), including *scope*: always-on, per-topic (plain for infra, expert for their home turf), or per-mood.
4. **Implement it in the harness**, not just in memory of the conversation: as an instruction block in this repo's agent-instructions file, or via the harness's native mechanism where one exists (e.g. [Claude Code output styles](https://code.claude.com/docs/en/output-styles)). The register must survive the session.

## The other dial: pace

The same tuning conversation applies to **slice size** — how much the agent does between check-ins (micro → small → chunk → run, defined in `agreements.md`). Voice is how it talks; pace is how much it does before asking. Diagnose, offer the ladder, record the setting, and re-tune when reactions change — exactly as with register.

## Re-tuning

Register drift is normal — expertise grows, patience shrinks. When the owner's reactions change (asking for explanations they used to skip, or skipping ones they used to need), offer a re-tune; the old register gets superseded in the ledger, never erased.

## Sources

- [Claude Code output styles](https://code.claude.com/docs/en/output-styles) — the harness-native mechanism: personas as markdown that reshape communication while keeping capabilities.
- [hesreallyhim/awesome-claude-code-output-styles-that-i-really-like](https://github.com/hesreallyhim/awesome-claude-code-output-styles-that-i-really-like) — curated community styles; the survey map for finding more registers.
- [JuliusBrussee/caveman](https://github.com/juliusbrussee/caveman) and [carlosduplar/caveman-output-style-claude-code](https://github.com/carlosduplar/caveman-output-style-claude-code) — the canonical silly-but-useful register: terse to the point of measurable token savings.
