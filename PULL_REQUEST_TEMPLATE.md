<!-- Org-wide default PR template. A repository may override it with its own.
     Fill the sections in rather than deleting them. See the repo's
     CONTRIBUTING.md for its specifics. -->

## Summary

<!-- What does this PR change, and why? -->

Closes #<!-- issue number; use "Refs #N" for related-but-not-closing, or delete if none -->

## Testing

<!-- How was this verified? Tests run, new tests added, manual checks.
     A bug-fix test should fail before the fix and pass after. -->

## Breaking changes

<!-- Renaming or removing a pinned public surface (public namespace vars, the
     API boundary, seeded vocabulary, interchange formats) is breaking. Describe
     the break and the migration, or write "None". -->

None

## Checklist

- [ ] Commit subjects are Conventional Commits — `type(scope): subject`, scope optional.
- [ ] Every commit is signed off under the DCO (`git commit -s`).
- [ ] I have signed the CLA, if this repo requires one (the SSPL-licensed engine does; the Apache-2.0 repos use DCO alone).
- [ ] Any `Co-Authored-By:` / `Co-developed-by:` trailers credit human collaborators only.
- [ ] New features and bug fixes have tests.
- [ ] The repo's test/lint gates pass locally.
- [ ] Updated any docs this change touches.
- [ ] Didn't `--no-verify` or amend already-pushed commits.
