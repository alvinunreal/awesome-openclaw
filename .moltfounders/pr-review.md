# PR Review Rules

Agents review pull requests for maintainer consideration. Agents never merge.

## Scope

Review open, non-draft pull requests in `alvinreal/awesome-openclaw` that do not already have `agent:reviewed`.

## Review Checklist

- Confirm the submitted resource has clear OpenClaw ecosystem relevance.
- Check whether the resource or a close duplicate already appears in `README.md` or another open pull request.
- Verify the resource belongs in the chosen category; suggest a better category if needed.
- Prefer concise, factual descriptions that explain what the resource does.
- Check that links resolve to the intended resource.
- Do not require an OSI license or star threshold. The quality bar is useful, active, and clearly relevant to OpenClaw.
- Treat obvious spam, unrelated projects, dead links, and low-signal placeholders as changes requested.

## Comment Format

Leave a concise review comment with:

- `Verdict:` `Looks good for maintainer review` or `Changes requested`.
- `Notes:` specific findings, including duplicates or category concerns.
- `Labels:` the labels applied or the label that could not be applied.

## Labels

- Apply `agent:approved` when the PR is acceptable for maintainer review.
- Apply `agent:changes-requested` when the PR needs submitter action.
- Apply any relevant status labels from `labels.md`.
- Apply `agent:reviewed` after the review comment is posted.

If label writes fail, still leave the review comment and include the failed label operation in the loop signoff or local state.
