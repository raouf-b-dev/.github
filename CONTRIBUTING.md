# Contributing

Thanks for contributing. These notes apply to repositories under [raouf-b-dev](https://github.com/raouf-b-dev) that use this account’s default community health files.

## Issues first

For larger changes (new features, behaviour changes, refactors that touch many files), open an issue first and wait for agreement on the approach. Small fixes and docs updates can go straight to a pull request.

## Branches

Branch from the repository’s integration branch:

- Ecommerce repos (`ecommerce-store-api`, `ecommerce-admin-dashboard`, `ecommerce-store-web`, `ecommerce-platform`): `develop`
- Other repos: the default branch shown on GitHub (often `master` or `main`)

Keep one focused pull request per change.

## Commits and pull requests

Use Conventional Commits for both commit subjects and PR titles:

```text
type(scope): subject
```

Examples: `fix(auth): reject empty refresh tokens`, `docs: clarify setup steps`.

Prefer signed commits (`git commit -S`).

Fill in the pull request template. Link an **issue** with `Closes #<number>` when one exists (not a pull request). Delete that line when there is no issue.

## Changelog

If the change is user-visible, add one bullet under `## [Unreleased]` in `CHANGELOG.md`. Do not put the PR number in the bullet. If nothing user-facing changed, leave the changelog alone (or note `None` in the PR template).

## Questions

Use GitHub Issues on the repository you are contributing to. For security vulnerabilities, follow that repository’s `SECURITY.md` (do not open a public issue).
