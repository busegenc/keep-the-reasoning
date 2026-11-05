# Checklist

Your side of the deal. The agent can show you evidence, list its decisions and quiz you — but only if you set that up and actually look.

See [LEVELS.md](LEVELS.md) for L1 / L2.

## Before you start

| Rule | L1 | L2 |
|---|---|---|
| Decide the risk level | ✅ | ✅ |
| Write a one-sentence hypothesis of the expected answer — even a bad guess | optional | ✅ |
| Ask: *what would have to be true for this to be wrong?* | — | ✅ |
| Brief: goal, out of scope, definition of done ([template](templates/task-brief.md)) | short | written |
| Define "verified" upfront — a test, a screenshot, a log | ✅ | ✅ |
| Ask: *am I using the agent to help me think, or to think for me?* | — | ✅ |
| If the problem is still fuzzy, have the agent interview you or run a blind-spot pass first | optional | ✅ |
| For open-ended decisions, have a model argue the opposite side before you commit | — | ✅ |

## While working

| Rule | L1 | L2 |
|---|---|---|
| After two rounds of corrections, stop patching and rewrite the prompt | ✅ | ✅ |
| Give critical source material directly — don't rely on chains of agent summaries | — | ✅ |

## When the output arrives

| Rule | L1 | L2 |
|---|---|---|
| Read the commands that ran and their real output **before** the summary | ✅ | ✅ |
| Read the agent's list of decisions and assumptions | skim | ✅ |
| For every green check, ask: *what did it prove? what didn't it prove?* | — | ✅ |
| Read the diff as if the AI didn't write it — transaction boundaries, flipped defaults, edge cases | — | ✅ |
| Pick 3 random lines — can you explain them? | — | ✅ |
| No merge until you pass the agent's quiz perfectly | — | ✅ |
| Signature test: *could I defend this in front of the person who maintains it?* | ✅ | ✅ |
| Write down one thing the agent didn't check | — | ✅ |

## Principles

- If you can't explain it, even with the agent's help, you've surrendered it.
- A green check proves one thing. Know which one.
- Polish is no longer a signal of quality.
- If you wouldn't put your name on it, it doesn't ship.
- You can offload the work. You can't offload the accountability.
