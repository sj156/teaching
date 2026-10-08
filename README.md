# Teaching

Reusable teaching workflows by **Sheng ([sj156](https://github.com/sj156))**, beginning with a Codex skill for drafting and improving lecture notes.

**Publicly viewable; all rights reserved.** This repository is not open source. Ask for permission before installing, using, adapting, or redistributing the materials beyond rights provided by applicable law or GitHub's terms. See [LICENSE](LICENSE).

## Lecture-notes skill

[`write-lecture-notes`](skills/write-lecture-notes/SKILL.md) supports drafting, extending, revising, and auditing course notes. Its conventions emphasize:

- Self-contained explanations, definitions followed by examples, and results followed by proofs and applications.
- Four subsection boxes: Core Reading, Guiding Questions, Review Questions, and Further Reading.
- Motivated exercises, computational investigations, and concept-driven figures.
- Consistent notation, verified reading references, and work proportional to the requested edit.

These are author-developed teaching conventions, not universal requirements. Explicit instructor requests and established course conventions take precedence. The detailed statistical examples and R/ggplot2 guidance reflect the skill's origins in statistics teaching; adapt them explicitly for another discipline or software environment.

The package contains instructions and seven supporting references. The skill itself does not include lecture manuscripts, datasets, private course files, or a hosted service. The accompanying [LaTeX style](latex/README.md) is provided separately from the skill; its installation, dependencies, and package options are documented there. It does not install required authoring software. Mathematical claims, citations, code, and rendered documents still need verification.

## Request permission

Open a GitHub issue describing your intended use and requested scope. Do not post private course material or personal information in the issue. Public access and citation alone do not grant reuse permission. Permission must be obtained before following the installation instructions below.

## Install in Codex (after permission)

Clone this repository, then run the following from its root on macOS or Linux. The destination check prevents overwriting an existing skill:

```sh
mkdir -p "$HOME/.agents/skills"
if [ -e "$HOME/.agents/skills/write-lecture-notes" ]; then
  echo "Skill already exists; compare and back it up before updating."
else
  cp -R skills/write-lecture-notes "$HOME/.agents/skills/"
fi
```

Keep the entire skill directory, including `references/`. Codex detects local skills; restart it if the skill does not appear. Avoid installing duplicate copies under multiple skill directories. See the [official skill documentation](https://learn.chatgpt.com/docs/build-skills).

Example request:

> Use the write-lecture-notes skill to draft a subsection on conditional probability for second-year undergraduates. Use the course files in the current project and preserve its notation and style.

For a focused edit:

> Use the write-lecture-notes skill to correct this proof only. Preserve the surrounding organization and exercises.

Tell Codex the course level, source location, output format, notation, and any departures from the default conventions. Keep personal paths and local preferences in your course project.

## Updates and maintenance

The installed skill is a copy; `git pull` alone does not update it. Authorized users should review [CHANGELOG.md](CHANGELOG.md), back up local customizations, and replace their installed skill directory with the selected release. Do not merge course-specific edits into the shared copy unintentionally.

Maintainers should edit the repository source, check relative links and personal information, and test representative drafting, revision, exercise, and narrow-correction requests. Update the changelog and tag releases. Retain previous releases for recovery. See [maintenance cases](docs/maintenance-cases.md).

## Attribution

See [CITATION.cff](CITATION.cff) for citation metadata and [AUTHORSHIP.md](AUTHORSHIP.md) for provenance. Attribution does not replace permission. Bug reports and suggestions are welcome; please discuss proposed contributions before submitting changes so their rights can be agreed explicitly.
