# Contributing

This document describes the contribution process across all genOTC repositories.

## Branching

- Branch from the default branch.
- Use short, descriptive branch names.
- Include the issue ID in the branch name to link the issue automatically (e.g. `gen-123-short-description`).
- Keep branches short-lived.

## Commits

- Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification (`type(scope): subject`).
- Write commit messages in lowercase only.
- Write commit messages in the imperative mood.
- Keep each commit focused on a single concern.
- Reference relevant context (issue, ticket, discussion).
- Never commit secrets, credentials, or production data.

## Versioning

- Follow [Semantic Versioning](https://semver.org/) (`MAJOR.MINOR.PATCH`) for all released artifacts.
- Conventional commit types drive version bumps: `fix:` → PATCH, `feat:` → MINOR, `BREAKING CHANGE:` footer or `!` suffix → MAJOR.

## Pull requests

- Open one pull request per logical change.
- Keep pull requests as small as possible to ease review and reduce risk.
- Run an auto-review before requesting human review.
- Fill in the pull request template in full.
- Ensure continuous integration passes before requesting review.
- Request review from a relevant maintainer (CODEOWNER).
- Update documentation in the same pull request as the code change.

## Code review

- Review for correctness, clarity, and maintainability.
- Address all blocking comments before merging.

## Testing

- All non-trivial changes must include or update relevant automated tests.
- Manual verification alone is not sufficient.

## Engineering principles

- Correctness over cleverness.
- Small, focused changes.
- Tests are not optional.
- Document the why, not the what.
- Leave the code better than you found it.
