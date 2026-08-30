# Staleness Rules

Agents help surface old issues and pull requests without closing them unilaterally.

## Scope

Review open issues and pull requests in `alvinreal/awesome-openclaw`.

## Windows

- Consider an issue or pull request stale after 30 days without meaningful activity.
- Consider `needs-info` items stale after 14 days without a submitter response.
- Do not mark an item stale if a maintainer commented in the last 14 days.

## Actions

- For stale issues, post a short reminder asking whether the item is still relevant, then apply `stale`.
- For stale pull requests, post a short reminder asking the author to rebase, respond, or confirm the resource is still relevant, then apply `stale`.
- Apply `needs-human` when the next step requires maintainer judgment.
- Never close issues or pull requests.
- Do not repeat a stale reminder if an agent already posted one recently.

## Comment Format

Use a concise comment that states the item appears inactive and identifies the next expected action. Avoid long summaries.
