# Computation and self-contained examples

Use within the requested lecture scope. Figure evidence and rendering are covered in [figures](figures.md).

## What students need

- Notes must contain the setup, data access, consequential parameter choices, mathematical steps, results, and interpretation needed to understand each example. Earlier material may be referenced; a script or notebook cannot replace the argument.
- Print small teaching datasets compactly, with units and meaningful indices, unless an informative plot plus exact data/access suffices. For large datasets give an appropriate preview or summary and fully specified preparation. Identify sufficient statistics as summaries and explain their role under the stated model.
- Use language-neutral pseudocode for core procedures, with explicit inputs, outputs, loops, sampling/update operations, and accuracy checks. Specify how unknown parameters and tuning are obtained. Keep routine implementation logistics in authoring source. Use runnable code in notes only when language-specific implementation is a learning objective or the instructor requests it; define its inputs and helpers.
- Give shared algorithms and simulation protocols one primary home, then specify only application-specific changes. Avoid duplicating a resampling recipe for every smoother. Keep meaningful distinctions in target, noise model, tuning, and calibration explicit.
- Put core algorithms in the existing numbered algorithm environments, not a parallel class of prose-only pseudocode examples. Inspect the project style first; the separately supplied `myMath-notes` style provides `algorithm` and `algpseudocode` when used. Number within subsections with unique hyperlink anchors and stable labels.
- Add a schematic when dependencies, shared quantities, iteration, or branches need visual explanation. Show the flow rather than repeating every pseudocode line; reuse a faithful existing diagram.

## Authoring and verification

- Reproducible scripts generating requested figures, tables, and numerical checks are part of authoring the notes. They do not require creating a student companion. Retain seeds and necessary implementation details in source; state them in the notes when needed for an assigned experiment.
- Keep model/input data, varied factors, controls, measured quantities, and simulation uncertainty explicit. Verify reported results under the stated setup, and distinguish executed evidence from proposed experiments. Use the course's language and minimal dependencies.
- Develop integrated investigations when they add statistical insight beyond local mechanics. Connect computation to a question, evidence, interpretation, and limitations; avoid complexity for its own sake.
- Keep master preambles minimal. Reusable layout and numbering belong in the course style; use explicit options to preserve document-specific behavior without changing other courses' defaults.

## Student companions, when requested

- Follow the course software choices; by default, use one course-wide R Markdown companion organized by lecture section numbers. Match its examples to the notes and include data, complete code, outputs, plots, checks, interpretation, and a small extension. Use fixed seeds and verify rendering from a fresh session.
- Keep the notes primary and grow the companion incrementally. Do not migrate unrelated sections or build an elaborate publishing system. The companion supplements rather than replaces essential procedures, reasoning, figures, and conclusions in the notes.
