# Contributing

This repo practices what it preaches: no rule gets in without evidence.

## Proposing a rule

Open an issue with the **Rule proposal** template. Every proposal answers three questions:

1. **The failure** — what actually went wrong in your agent work? A real case, not a hypothetical.
2. **The catch** — how would this rule have caught it, and at which step (before / during / after)?
3. **The cost** — what does following the rule cost every time? Is it worth it at L1, or only at L2?

## Keep it small

- The agent rules have a hard cap of **12 rules**. Rules nobody reads protect nobody. To add one, merge or remove another.
- One rule, one behavior. If it needs a paragraph to explain, it's probably two rules or a template.
- Prefer rules that produce **evidence** (something you can look at) over rules that ask for good intentions.

## Keeping the tool files in sync

The four files in `agent-rules/` carry the same rules in different formats. A rule change must update all four in the same pull request.

## Translations

Add translations under `translations/<language-code>/`, mirroring the English file names. Translations may lag behind; note the English commit they're based on at the top of each file.

## Adapt instead of upstreaming

If a rule only makes sense for your team, your stack or your domain, it belongs in your fork — that's the point. Upstream is for rules that help most people.

## License

By contributing, you agree your contributions are licensed under [CC BY 4.0](LICENSE).
