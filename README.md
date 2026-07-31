# .github

The **`vaelii` organization's special `.github` repository**. It is not a
code project — it holds two things:

1. **The org profile** — [`profile/README.md`](profile/README.md) renders on the
   organization's GitHub landing page.
2. **Default community-health files** — GitHub uses these as the fallback for
   *every* repo in the org that doesn't ship its own copy:
   - [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md)
   - [`SECURITY.md`](SECURITY.md)
   - [`SUPPORT.md`](SUPPORT.md)
   - [`CONTRIBUTING.md`](CONTRIBUTING.md)
   - [`GOVERNANCE.md`](GOVERNANCE.md)
   - [`FUNDING.yml`](FUNDING.yml)
   - [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) and [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md)

Issue templates are the one type GitHub pins to a folder: they must be in
`.github/ISSUE_TEMPLATE`. Everything else may be at the root.

A repository that ships its own version of any of these **overrides** the
default — so per-repo specifics (e.g. a project's own security scope or
contribution terms) still win.

## What does *not* live here

`LICENSE`, a project `README`, `DCO`, CLA files (`legal/`) and workflows are
**not** inherited by GitHub — they must live in each repository. Vaelii's
licenses vary by project (SSPL-1.0 for the engine, Apache-2.0 for the reader
plugin, and other terms for what is not published yet), so a single org-wide
license would be wrong.

## Editing

Change a file here and every repo without its own copy picks it up
automatically — there is nothing to sync, and no staging either, so review
before pushing.
