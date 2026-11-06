# CLGZ .github repository instructions

## Scope and sources

- These instructions govern changes within `CLGZcomLLC/.github` only. An `AGENTS.md` here does not automatically apply to other organization repositories.
- The current repository contains [README.md](README.md) and no application, workflow, package manifest or test runner. Inspect the current tree before assuming organization profile content, templates, community-health defaults or reusable workflows exist.
- Keep any public-facing guidance accurate and free of private client details, credentials or internal operational information. Adding organization-wide defaults or reusable workflows requires an explicitly scoped change and impact review.

## Working and tracking rules

- Inspect the current Git/GitHub state and applicable nested instructions before changing files. Verify the live default branch and preserve unrelated work and published history.
- Search existing issues before creating a focused tracking issue. Use a `codex/` branch and an issue-linked PR; keep the diff limited to the request. Do not force-push or rewrite history.
- Keep secrets, credentials and private customer information out of source, logs, issues and artifacts. Use synthetic fixtures and sanitized evidence.
- Record risk, changed behavior, validation, remaining limits and rollback in the repository issue/PR. Separate implementation, merge, deployment and acceptance evidence.

## Validation and delivery boundaries

- Validate only the documentation/assets actually changed: Markdown structure, relative links, intended audience and the final Git diff. No application test/build command is currently defined.
- Do not create cloud resources, alter organization settings, modify other repositories or publish runtime services during repository documentation maintenance.
- A PR or merge here is repository delivery, not proof that another repository adopted its content. Verify supported GitHub default-file behavior separately before claiming organization-wide effect.

## Instructions-only verification and rollback

- For changes confined to this file, check Markdown, local paths/links, named commands against the current tree and `git diff --check`. Run independent static checks; an application rebuild or deployment is not required for prose alone.
- For code changes, run the narrowest relevant existing checks and scale coverage to risk. Report unavailable tooling and failed/skipped checks accurately. After two failed fix/retest cycles, escalate or reduce scope instead of looping.
- Release note and test evidence belong in the linked issue/PR. Roll back instruction changes with a focused revert PR; do not change runtime services as part of that rollback.
