# open-AWS-scanner Development Log

## 2026-09-22 — Monthly maintenance and release automation

- Updated package metadata links to the CloudBannaPepper GitHub repository.
- Added monthly Dependabot checks for Python and GitHub Actions dependencies.
- Added a scheduled monthly release workflow that runs smoke checks, bumps the
  patch version when changes exist, creates a GitHub Release, and skips empty
  releases.
- Added release-summary delivery through the CloudBananaPepper contact API's
  protected `/internal/alert` route.
