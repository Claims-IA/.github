# Organization community defaults

[PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md) supplies the French PR body
for repositories that inherit the organization default. A repository-specific
template takes precedence; this change does not replace those local templates.

Keep Quoi, Pourquoi, Hors-périmètre and Points d’attention, plus a verification
section distinguishing passed, failed, unavailable and not-applicable checks.
Retain the conditional AI-disclosure footer when it applies. Avoid product-specific
examples so small libraries, documentation and infrastructure projects can use it.

This is a public repository. Review every example, link and PR body for private
information before publication. Describe organization-wide effects in template PRs.
No workflow, permission, deployment or automatic rollout is configured here.

Read [AGENTS.md](AGENTS.md) and [REVIEW.md](REVIEW.md) for this repository’s own
maintenance rules. These files do not inject agent instructions into other
repositories; adopted projects must commit their own local entrypoints and rules.
