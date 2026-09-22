# open-AWS-scanner Development Log

## 2026-09-22 — Monthly maintenance and release automation

- Updated package metadata links to the CloudBannaPepper GitHub repository.
- Added monthly Dependabot checks for Python and GitHub Actions dependencies.
- Added a scheduled monthly release workflow that runs smoke checks, bumps the
  patch version when changes exist, creates a GitHub Release, and skips empty
  releases.
- Added release-summary delivery through the CloudBananaPepper contact API's
  protected `/internal/alert` route.

## Commit-level backfill — 2026-08-01 through 2026-09-22

The following commits occurred after the previous DEVLOG entry. Checkpoint,
snapshot, and CI-trigger commits are retained so the development history is
complete.
- 5b34909 feat: email monthly release summaries
- d797a09 fix: set package repository links
- 4203016 Create SECURITY.md
- e54c1cf chore: automate monthly scanner releases
- fa95d2c Commit pending CloudBananaPepper updates
- bdc084e Checkpoint current changes
- 88a828d chore: migrate CloudBannaPepper branding and domains
- ed1047f Allow manual package release runs
- 419e227 Enable PyPI release workflow
- 34adb4c Release open-aws-scanner 0.3.5
- 0b6a9e8 Make idle NAT detection dependency aware
- 54c1c18 Disable GitHub workflows
- 71bad79 chore: remove repo-local devlogs
- 4c29c44 docs: close out daily delivery updates
