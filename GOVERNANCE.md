# Governance

How decisions get made across Vaelii repositories. Vaelii is a small project;
this describes the model as it stands and will formalize as it grows.

## Steward

Vaelii is a **single-steward, open-contribution** project. **Vaelii LLC** is the
steward: it holds the "Vaelii" name and marks, owns the domain, and is the grantee
of the Contributor License Agreement. Stewardship exists to keep the project
coherent and to protect its licensing position — not to gatekeep good
contributions.

## Roles

- **Maintainers** review and merge changes, cut releases, and set technical
  direction. They have final say on what merges.
- **Contributors** are anyone who opens an issue, a discussion, or a pull
  request. You don't need to be a maintainer to shape the project — most changes
  start as a contributor's issue or PR.

## Decisions

- **Everyday changes** proceed by lazy consensus: a PR that passes review and CI,
  with no maintainer objection, merges.
- **Larger or contentious changes** (public API, KB schema, licensing, anything
  breaking) are decided by the maintainers, ideally after discussion in an issue.
  When maintainers disagree, the steward decides.
- **Roadmap and priorities** are owned by the maintainers / steward. Community
  input via issues is welcomed and weighed, but the project is
  not run by open vote at this stage.

## Licensing & the CLA

Licenses vary **by repository** — the engine (`vaelii`) is SSPL-1.0, the reader
plugin (`vaelii-foreign`), the storage adapters (`vaelii-postgres`,
`vaelii-sqlite`) and the model-provider clients (`vaelii-agents`) are
Apache-2.0, and repositories published later carry their own terms
(knowledge-base data will be CC BY). The
CLA (required by the SSPL repos; see each repo's `legal/`) assigns Vaelii LLC the
rights needed to steward the license over time, including relicensing to an
OSI-approved license without re-contacting every contributor. A move to a *more*
open license takes nothing away from contributors or users. See each repo's
`CONTRIBUTING.md` and `LICENSE`.

## Trademark

"Vaelii" and associated marks are held by Vaelii LLC. The source licenses do not
grant trademark rights; don't use the name in a way that implies official status
without permission.

## Changing this document

Governance changes are made by the steward, normally after discussion. Contact:
**support@vaelii.com**.
