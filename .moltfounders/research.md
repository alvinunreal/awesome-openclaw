# Research Rules

Agents may suggest high-signal OpenClaw ecosystem resources through pull requests.

## Scope

Research should add at most five qualifying resources per cycle and avoid duplicating existing README entries or open pull requests.

## Candidate Bar

A candidate should:

- Be clearly useful to OpenClaw users, operators, plugin authors, skill authors, or adjacent OpenClaw-style agent workflows.
- Have a reachable canonical URL.
- Show enough activity, documentation, or adoption to be useful to readers.
- Fit one existing README category cleanly.

Do not require an OSI license or a minimum star count. Do skip low-effort placeholders, generic AI tools with no OpenClaw relevance, spam, and abandoned resources with no useful documentation.

## README Format

Use the local README format already present in the target section:

```markdown
- [owner/name](https://github.com/owner/name) ![GitHub Repo stars](https://img.shields.io/github/stars/owner/name?style=social) - Concise factual description.
```

Keep descriptions short and specific. Avoid marketing language.

## PR Rules

- Work on a branch named `research/<date>-<category>` when practical.
- Commit with `Add: <Name> to <Category>` for a single-resource addition, or a concise research summary for multiple additions.
- Create a PR titled `[Research] Add entries to <Category> - <Date>`.
- Apply `agent:suggested` and `agent:reviewed` if label permissions allow.
- Never merge the PR.
