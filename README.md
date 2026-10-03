# QuickCasa/.github

This repository holds the organization-wide defaults for QuickCasa's public
repositories on GitHub.

- `profile/README.md` is the page visitors see at
  [github.com/QuickCasa](https://github.com/QuickCasa).
- `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md` and `SUPPORT.md` apply
  to any repository that doesn't have its own copy of that file.
- `.github/ISSUE_TEMPLATE/` holds the default issue forms, and
  `.github/pull_request_template.md` the default pull request template. If a
  repository has any files in its own `.github/ISSUE_TEMPLATE` folder, it uses
  only those.

## New public repositories

Set each new public repository up the same way:

1. Start from a fresh repository and copy the code in, so no internal history or
   configuration comes with it.
2. Turn on private vulnerability reporting in the repository's security
   settings. `SECURITY.md` sends reporters there, and the button only appears
   once it's on.
3. Turn off the wiki and projects, allow only squash and rebase merges, and turn
   on deleting branches after a merge.
4. If GitHub Pages deploys from a release tag, add a `v*.*.*` tag rule to the
   `github-pages` environment. Without it, the deploy fails with an environment
   protection error.
5. Add the project to the list in `profile/README.md`.
