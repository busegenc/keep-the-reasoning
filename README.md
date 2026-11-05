# keep-the-reasoning

**Offload the work to AI agents. Keep the reasoning.**

As models get better, obvious errors get rarer. Most agent output is well-written and mostly correct — which is exactly why it stops demanding a second look. Step by step, you drift from *delegating* a task to *surrendering* it: the output quietly becomes yours without you being able to explain it.

This repo is a small, adaptable rule set for staying the owner of what your agents produce. It has two sides:

- **For you:** a [checklist](checklist.md) that scales with risk, plus weekly and monthly [rituals](rituals.md).
- **For your agent:** drop-in rules for [Claude Code](agent-rules/CLAUDE.md), [AGENTS.md](agent-rules/AGENTS.md)-compatible tools, [Cursor](agent-rules/cursor.mdc) and [GitHub Copilot](agent-rules/copilot-instructions.md).

Everything scales by **two [risk levels](LEVELS.md)**, so a throwaway script doesn't get the same ceremony as a payments migration.

## Quick start (2 minutes)

1. Copy the agent rules for your tool into your project:

   | Tool | Copy | To |
   |---|---|---|
   | Claude Code | `agent-rules/CLAUDE.md` | `CLAUDE.md` (or append to yours) |
   | Codex & AGENTS.md tools | `agent-rules/AGENTS.md` | `AGENTS.md` |
   | Cursor | `agent-rules/cursor.mdc` | `.cursor/rules/keep-the-reasoning.mdc` |
   | GitHub Copilot | `agent-rules/copilot-instructions.md` | `.github/copilot-instructions.md` |

2. Set the risk level at the top of the file: `L1` or `L2`.
3. Open [`checklist.md`](checklist.md) at the start and the end of agent work.
4. Optional: use the [templates](templates/) for briefs, agent reports and pull requests.

## What's inside

| File | What it's for |
|---|---|
| [`LEVELS.md`](LEVELS.md) | How to pick L1 or L2 |
| [`checklist.md`](checklist.md) | Your before / during / after checklist |
| [`agent-rules/`](agent-rules/) | The same rules, formatted per tool |
| [`templates/task-brief.md`](templates/task-brief.md) | Write your intent before you prompt |
| [`templates/agent-report.md`](templates/agent-report.md) | The report shape to ask agents for — evidence first |
| [`templates/pull_request_template.md`](templates/pull_request_template.md) | PR template with "what would these checks miss?" |
| [`rituals.md`](rituals.md) | Weekly and monthly calibration |
| [`translations/`](translations/) | Translations (Turkish available) |

## Make it yours

These rules are a starting point, not a standard. Fork the repo and change the levels, drop rules that don't earn their place, add the ones your own failures taught you. If a rule would help most people, [propose it](CONTRIBUTING.md).

## Credit

Adapted from Addy Osmani's article **[Critical thinking when agents do the work](https://x.com/addyosmani/article/2117512471930167377)**. The article's text is not reproduced here; the rules are an original, practical adaptation of its ideas. Read the original — it's worth it.

## License

[CC BY 4.0](LICENSE) — use, share and adapt freely, with attribution.

---

Maintained by [@busegenc](https://github.com/busegenc).
