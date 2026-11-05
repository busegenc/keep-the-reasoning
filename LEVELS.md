# Risk levels

Not every task deserves the same rigor. Applying every rule to every task isn't sustainable — and rules you can't sustain get skipped exactly when they matter. Pick a level before you start.

## L1 — Low stakes

Prototypes, personal scripts, experiments, spikes, internal tooling only you use — anything that's cheap to be wrong about and easy to undo.

You can delegate fully. Still:
- look at the evidence (what ran, what it returned) before the summary, and
- pass the signature test: *would I put my name on this?*

## L2 — High stakes

Production systems, auth, payments, data migrations, anything touching user data, code someone else will maintain, anything hard to reverse.

Every rule applies.

## How to decide

Ask one question: **if this is wrong, will someone else have to deal with the consequences?**

- No → L1. Take the handoff.
- Yes → L2. Keep the reasoning.

**When unsure, it's L2.**

A project can contain both: a repo can default to L1 while a specific task (say, a schema migration) is run as L2. Say so in your brief.
