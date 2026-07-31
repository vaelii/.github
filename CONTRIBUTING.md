# Contributing to Vaelii

This is the organization-wide **default**. Each repository has its own
`CONTRIBUTING.md` with the specifics for that project — **if a repo has one, it
takes precedence over this file.** Read the repo's own guide first; this one
covers what's common to all Vaelii repositories.

## Before you start

- For anything non-trivial, open an issue to align on the approach before
  writing code — it saves a round trip.
- Be kind. All participation is governed by our [Code of Conduct](CODE_OF_CONDUCT.md).

## Sign your commits (DCO)

Every commit must carry a `Signed-off-by` line certifying the
[Developer Certificate of Origin](https://developercertificate.org/) — add it
with `git commit -s`. Each repo also ships the DCO text as a `DCO` file at its
root. Unsigned commits can't be merged.

## Contributor License Agreement (some repos)

The **SSPL-licensed** engine (`vaelii`) additionally requires a signed
Contributor License Agreement — the `ICLA.md` (individual) and `CCLA.md`
(corporate) live under that repo's `legal/`. This lets Vaelii LLC steward the
license (including an eventual move to an OSI-approved license without
re-contacting every contributor). The **Apache-2.0** repositories, such as
`vaelii-foreign`, use the DCO alone — no CLA. The repo's own `CONTRIBUTING.md`
and `LICENSE` say which regime applies.

## Making a change

1. Fork and branch off the repo's contribution target branch — `develop` on the
   published repos, where `main` carries releases and is never a pull-request
   target. The repo's `CONTRIBUTING.md` is the authority.
2. Keep changes focused; match the surrounding code's style and conventions
   (each repo documents its own in `docs/` and its `CONTRIBUTING.md`).
3. Add or update tests, and make sure the repo's test/lint gates pass locally.
4. Open a PR with a clear description of what and why. Sign off your commits.

## Reporting

- **Bugs / features:** issues on the relevant repository, using its template.
- **Security vulnerabilities:** never a public issue — see [`SECURITY.md`](SECURITY.md).
- **Commercial licensing / private inquiries:** support@vaelii.com.
