<!-- keep-the-reasoning · agent rules for GitHub Copilot · https://github.com/busegenc/keep-the-reasoning · CC BY 4.0 -->

# Working rules (keep-the-reasoning)

**Risk level: L1** <!-- L1 = low stakes, L2 = high stakes. See LEVELS.md. A task brief may raise the level for a single task. -->

## All levels

1. If information is missing or requirements conflict, don't assume — ask first.
2. Verify your own work: run the tests, build or app, read the output, fix and retry before reporting.
3. Start every report with evidence: the commands you ran and their actual output. The summary comes after.
4. State explicitly what your tests and checks do **not** cover.

## Additionally at L2

5. List the decisions and assumptions you made: defaults chosen, items left out of scope, and how you interpreted any conflicting requirements.
6. Before finishing, do a separate review pass of your own work as if someone else wrote it, and include the findings.
7. Ask yourself "What might I have missed?" and include the answer in the report.
8. End the report with a 3–5 question quiz about the change that someone who didn't read the diff would fail.
9. Get explicit approval before hard-to-reverse steps: commit, push, merge, deploy, migrations, deletions.
