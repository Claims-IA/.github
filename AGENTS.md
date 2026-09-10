<!-- shared-guidance:begin -->
## Shared engineering rules

Before relevant work, read the locally committed rules below and
[REVIEW.md](REVIEW.md) before reviewing. These links are required reading,
not automatically discovered instruction files. Preserve stricter local rules.

- Read [development](.engineering/standards/development.md).
- Read [documentation](.engineering/standards/documentation.md).
- Read [git](.engineering/standards/git.md).
- Read [review](.engineering/standards/review.md).
- Read [verification](.engineering/standards/verification.md).

Read applicable nested instructions before changing their areas.
See [.engineering/NOTICE.md](.engineering/NOTICE.md) for attribution.
<!-- shared-guidance:end -->

# Project contributor guide

## Purpose

This public repository maintains organization community defaults. Its pull-request template is inherited by repositories without a local override; the agent instructions here govern this repository only.

## Map

- [PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md): the organization default PR body.
- `.engineering/`: selected rules, attribution and adoption metadata committed locally.
- [REVIEW.md](REVIEW.md): public-safety and organization-wide review priorities.

## Protected state and authority

Keep every tracked file and PR public-safe. Do not include private repository identifiers, customer names, internal URLs, credentials, or workstation paths. Template edits affect repositories inheriting the default; no organization settings or permissions are changed by this guidance.

## Contribution base and metadata

The contribution base is `main`. Use `feature/<work-description>` without a real ticket; preserve the actual ticket convention when supplied. Use normal follow-up commits, genuine authorship, and the organization French PR structure with its conditional disclosure footer. Merge and deployment require separate authority.

## Verification

Markdown and JSON only: validate local links, placeholders, managed fingerprints and `git diff --check`. There is no application runtime, package installation, application test suite or tracked CI workflow. Inspect the full template diff for organization-wide implications and privacy.

## Canonical documentation

Maintain the single [organization PR template](PULL_REQUEST_TEMPLATE.md). Keep its French Quoi, Pourquoi, Hors-périmètre, Points d’attention structure and conditional AI-disclosure footer. A local repository template should exist only for substantive project-specific requirements.

## Nested guidance

No nested instructions or overrides are currently tracked. Root AGENTS.md explicitly routes to local rules; organization defaults do not automatically inject agent instructions into other repositories.

## Code Review Rules

Read the root REVIEW.md and relevant nested guidance before reviewing.

Rédiger les reviews en français. Vérifier le caractère public de tout exemple, les effets sur les dépôts héritant du modèle et la conservation du footer de divulgation. Ne pas imposer une stack, des tests applicatifs ou des tickets inexistants.
