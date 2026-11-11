# Release Checklist

Short checklist for the release manager drill. Each item below must be checked off before a release candidate is promoted.

- [ ] Verify all tests pass on the default branch (`main`) and on `drill/notes`.
- [ ] Confirm version bump and changelog are updated in `RELEASE_NOTES.md`.
- [ ] Run the automated CI pipeline (lint, unit tests, build) and collect the results.
- [ ] Review the diff of `RELEASE_NOTES.md` with a code review comment before merging.
- [ ] Merge the PR, tag the release, and archive the checklist as signed off.
