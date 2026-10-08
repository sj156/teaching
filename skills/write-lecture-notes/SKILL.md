---
name: write-lecture-notes
description: "Draft, extend, revise, and audit course lecture notes or teaching modules across disciplines. Use when the user requests lecture notes, a textbook-style course chapter, or an editorial audit of definitions, proofs, examples, investigations, headings, and pedagogical structure. Apply these standards to existing LaTeX notes as well as new material."
---

# Write Lecture Notes

Create rigorous, self-contained notes that students can study independently. Preserve the course level, style, and authoritative files. Use the authoritative course sources identified by the user or project; an explicit user location takes precedence. Resolve the source location before editing rather than substituting a stale mirror.

A complete subsection being drafted or substantively revised requires exactly one Core Reading, Guiding Questions, Review Questions, and Further Reading box, in the prescribed order, verified reading references, coverage of each key concept by exercises, and at least three substantive exercises. Subsubsections do not get separate sets. These requirements do not expand an incidental edit into subsection redevelopment.

Keep section preludes motivational: exclude learning-objective lists and computational-convention statements, and place technical remarks in the relevant subsection or subsubsection. Apply conventions consistently throughout the notes. Build comprehensive exercise banks connecting phenomena, technical development, computational experiments, and simple real-data visualization.

Follow definitions immediately with worked examples; follow results with proofs or sketches and a calculation or example. Give each example a distinct conceptual purpose at the course level, retaining simple illustrations of abstract definitions. Use figures whose panels advance that purpose. Keep data, reasoning, outputs, and interpretations in the notes. Add or extend a computational companion only when requested; it does not replace self-contained exposition.

These are the default teaching conventions of this skill. Explicit instructor requirements and established course conventions take precedence when they conflict. Keep course-specific paths, audience, software choices, and style settings in the course project rather than hard-coding them here.

## Work proportional to the request

- Default to a focused edit: read the current target and enough surrounding definitions, sources, and dependencies to make the change reliably. Search headings or symbols before opening long files. Reuse context already read during this session unless it changed.
- For substantive development, apply the relevant standards across the requested section or artifact. A local correction does not trigger a full audit. Run a comprehensive audit only when requested; a request to improve a whole artifact still requires completing that whole scope.
- Work with one agent by default. Delegate only when the user requests delegation or an independent check is necessary to resolve a consequential uncertainty. Give any reviewer the smallest self-contained material and a distinct question; do not duplicate whole-document reviews.
- Load only the references whose triggers below match the work. Their words “every,” “all,” and “before delivery” apply within the active scope and affected dependencies, not automatically to the entire project. Combine overlapping checks into one pass.
- Reuse verified results, figures, citation checks, and build outputs when their inputs are unchanged. Use available deterministic checks for mechanical errors. Do not rerun research merely to edit its presentation.
- Check changed content and affected references once after editing. Repeat only for a new change, failed check, or unresolved substantive issue. For rendered artifacts, compile as appropriate and inspect affected pages; extend visual inspection when pagination or shared styling changes. Follow any required format-specific validation.
- Stop when the requested work and applicable checks are complete. Report material limitations and link deliverables briefly. Do not create audit reports, companion artifacts, extra experiments, or future work unless requested or necessary for the deliverable.

## Load guidance only when needed

- **Locating authoritative course files or planning/restructuring substantive sections:** [course-scope](references/course-scope.md).
- **Introducing or changing mathematical notation, model formulas, or statistical examples:** [notation](references/notation.md).
- **Drafting or substantively revising exposition, subsection boxes, definitions, results, or worked examples:** [exposition](references/exposition.md).
- **Developing or changing conceptual figures, example plots, or dataset introductions; includes ggplot2 EDA:** [figures](references/figures.md).
- **Adding data, algorithms, investigations, or requested companion code; includes numbering and schematic requirements:** [computation](references/computation.md).
- **Creating or changing exercises, or changing examples/figures on which exercises depend:** [exercises](references/exercises.md).
- **Completing a new module or conducting a requested comprehensive pedagogical audit:** [full-audit](references/full-audit.md).
