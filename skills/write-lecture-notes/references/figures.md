# Figures, tables, captions, and layout

Use the relevant sections below; a caption edit alone does not initiate a module-wide figure audit.

## Visual coverage and purpose

- Treat visual intuition as substantive teaching work. Aim to provide visual support for every retained example and illustration, including inline constructions and theoretical mechanisms. Preserve the instructor's carefully selected material and invest in missing visuals before treating revision as prose cleanup.
- For a coverage audit, map each item to a retained, new, redesigned, or explicitly shared visual. Scan included files and inline illustrations as well as numbered environments. A figure count or regex match is not proof of complete coverage. Keep this map outside student notes and report genuine gaps.
- A shared figure is appropriate when it faithfully explains each linked example; give a specific reading cue at each use. A generic thematic pointer does not cover a sample-specific calculation. If a compact table or calculation communicates an item better, record that reason instead of adding a decorative plot; honor explicit requests for figures.
- Give every panel a distinct purpose: mechanism, contrast, geometry, uncertainty, boundary, or failure. Identify the model, quantities, varied and fixed factors, and intended conclusion. Retain, combine, redesign, relocate, or remove panels by that purpose, not a quota.
- Preserve the phenomenon when choosing slices or simplifications. Before cosmetic restyling, consider overlays, common scales, local views, ratios, cumulative weights, or annotated thresholds. Compare methods on common data and tuning when isolating mechanisms; distinguish separately tuned comparisons and selected worst cases.

## Evidence and data

- Distinguish illustration, empirical evidence, and proof; exact, numerical, simulated, and schematic quantities. Generate curves from the stated procedures and retain reproducible code or vector sources. Never invent observations, sampling laws, optimizer paths, intervals, or failed-fit values.
- One realization does not establish bias, variance, risk, coverage, or universal rankings. Use exact analysis or repeated sampling with appropriate repetitions and Monte Carlo uncertainty. Shared randomness supports controlled comparisons; preserve visible simulation variation rather than replacing it with theory.
- Synthetic datasets require at least five observations and more for credible noise or heterogeneity; do not pad by duplication. Small symbolic constructions can isolate algebra but cannot substitute for empirical evidence; see [exercises](exercises.md).
- Introduce real datasets with purposeful ggplot2 EDA near their setup. State access, variables, units, sample size, grouping/time order, missingness, and preparation. Plot the analyzed sample, preserve ties or disclose jitter, and retain reproducible R source. Reuse views unless the question changes.
- Separate marginal/conditional effects, association/causation, exploration/validation, and numerical solvability/statistical stability. Mark computational failures separately. Put consequential qualifications in the nearby argument, without repeating generic warnings on every figure.

## Composition and captions

- Design at final display size. Keep labels readable, legends clear of curves, and encodings distinguishable without color. Compute limits from all compared curves, including tangents and reference laws. Reserve legend space rather than covering the feature being taught.
- Label units, normalization, and uncertainty targets. Use common scales for magnitude comparisons; a change of scale must be explicit. Prefer aligned panels for different units. Dual axes require distinct marks and an explanation that cross-scale heights, intersections, and slopes are incomparable.
- Keep figure and table captions to concise identification and essential decoding or setup, usually a short sentence. Put interpretation, derivation, and substantive qualifications in the nearby main text. Before moving caption text, check whether the body already says it: delete repetition, relocate only missing information, and preserve necessary setup. Do not replace a long caption with a duplicate long paragraph or impose an arbitrary word cap.
- Place visuals beside their argument. Synchronize captions, panel descriptions, labels, and dependent exercises after edits. Use stable cross-references; shared visuals need purposeful reading cues rather than copied explanations.

## Efficient verification and page layout

- Prefer exact vector graphics and modest computations with minimal dependencies. Verify numerical constructions before polishing. Never substitute prose for an unfinished essential figure and claim completion.
- Inspect assets in contact sheets, then check dense or suspect panels at reading size. After compilation, check missing references and overflow, survey affected page thumbnails, and inspect page breaks, proofs, and closing boxes. Asset inspection and successful compilation do not establish usable page layout.
- Reuse the available rendering runtime. For large batches, an in-process renderer such as `pypdfium2` can avoid repeated command startup; use an installed alternative when appropriate. Cache extracted page text and rendered thumbnails; rerender only changed assets and affected reflow. Do not install a new stack merely to follow a tool preference.
- Diagnose whitespace through floats, indivisible blocks, barriers, space reservations, and box padding. Fix locally; avoid global shrinking or forced floats. Prevent figures crossing topics, orphan headings, empty box fragments, and detached interpretations. Preserve required subsection starts and course typography; page-height changes are a last resort.
- More useful figures may legitimately increase pages. Measure actual page spans before claiming savings, and assess prose plus captions together before claiming concision. Refresh distributed PDFs after the final checked build; stop when correctness and readability are resolved.
