# Maintenance cases

Use these checks before a release. They are manual evaluation cases, not claims
that the current skill has passed a behavioral evaluation. Use a disposable
course project and supplied or verified sources.

| Case | Example request | Review criteria |
| --- | --- | --- |
| New subsection | Draft conditional probability for second-year undergraduates. | Audience-appropriate exposition; four ordered boxes; verified readings; examples and substantive exercises. |
| Focused correction | Correct only an algebraic error in this proof. | Correct mathematics; surrounding structure preserved; no full-module rewrite. |
| Figure and exercise | Improve a sampling-distribution figure and its dependent exercise. | Truthful setup, reproducibility, readable rendering, aligned exercise, no invented results. |
| Instructor override | Use Python and the existing course notation instead of the defaults. | Explicit choices respected; no forced R workflow or notation replacement. |
| Missing prerequisite | Revise notes whose source folder or required style is unavailable. | No stale-source substitution or claim of successful compilation. |

Check all relative links from the skill entry point. Search for personal paths,
credentials, private course identifiers, and unintended manuscript files. Read
the diff and changelog, record which behavioral cases were actually run, and
report any untested cases. Do not rerun an entire course-generation workflow for
a spelling correction.

For a release, choose a version, move the relevant changelog entries under it,
commit the reviewed files, and tag the commit. Keep the repository as the source
of truth for this public edition; personal installations are separate copies.
