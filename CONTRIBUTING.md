# Contributing

This is the default contributing guide for QuickCasa's open source repositories.
If a repository has its own `CONTRIBUTING.md`, follow that one instead. It covers
the project's scope and setup.

## Before you start

- **Search the existing issues.** Someone may already be working on it.
- **Open an issue before a large pull request.** Our projects keep a narrow
  scope on purpose, and asking first can save you building something we'd have
  to decline.
- **Never report a security problem in public.** Follow the
  [security policy](https://github.com/QuickCasa/.github/blob/main/SECURITY.md)
  instead.

## Pull requests

- Keep each pull request to one change, and explain why it's needed.
- Run the project's check script before you open it. In our TypeScript projects
  that's `npm run check`, which runs the same steps as CI.
- Add or update tests for anything you add or fix.
- If users will notice the change, add an entry to `CHANGELOG.md` under an
  "Unreleased" heading.

We squash or rebase pull requests when we merge them, so you don't need to tidy
your commit history.

## Code style

- TypeScript in strict mode. Avoid `any` and `unknown` and use specific types.
- Prettier formats the code. Run the project's format script before you commit.
- Use full words for names, such as `preferences` rather than `prefs`.
- Comments explain the reasoning the code can't show. Public functions get a
  JSDoc block.
- Every regular expression uses the `u` flag.
- User-facing text uses Canadian spelling, such as "colour" and "centre".

## Licence

Each repository's licence is in its `LICENSE` file. When you open a pull
request, your contribution is released under that same licence, as
[GitHub's terms of service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service#6-contributions-under-repository-license)
set out.

## Code of conduct

Everyone taking part is expected to follow our
[code of conduct](https://github.com/QuickCasa/.github/blob/main/CODE_OF_CONDUCT.md).
