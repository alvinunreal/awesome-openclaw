# Label Rules

These labels support automated maintenance. Keep names stable so agents can make idempotent decisions.

## Agent Labels

| Label | Use |
| --- | --- |
| `agent:reviewed` | An agent completed the applicable review or triage pass. Agents must skip items carrying this label. |
| `agent:commented` | An agent left a substantive comment. |
| `agent:approved` | An agent found a pull request acceptable for maintainer consideration. This is not merge approval. |
| `agent:changes-requested` | An agent found issues that should be addressed before maintainer review. |
| `agent:suggested` | An agent created or suggested an entry through the research loop. |

## Status Labels

| Label | Use |
| --- | --- |
| `needs-human` | The item needs maintainer judgment or external input. |
| `stale` | The item has had no meaningful activity for the staleness window. |
| `duplicate` | The resource or request already exists in the list or in another open item. |
| `not-openclaw-related` | The item lacks clear OpenClaw ecosystem relevance. |
| `needs-info` | More information is required from the submitter. |
| `broken-link` | A submitted link is unavailable or resolves to the wrong resource. |
| `license-issue` | Licensing is unclear or incompatible with the submitted resource. |
| `inactive` | The resource appears inactive by the current project freshness bar. |

## Application Rules

- Create any missing labels before applying them.
- Do not remove human-applied labels unless a maintainer explicitly requests it.
- Apply `agent:reviewed` only after the required comment and status labels are in place.
- Use `needs-human` instead of guessing when a decision depends on maintainer intent.
