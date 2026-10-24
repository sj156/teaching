# Create Homework: design

Apply these standards within the scope selected in [SKILL.md](../SKILL.md). This reference does not initiate a separate review pass or expand the task.

## Start from the course and the current artifact

- Read the relevant lecture sections and existing homework before drafting. Locate named theorems by content and verify numbering when possible; do not infer a theorem from its number alone.
- Follow the lecture notation, distribution parameterizations, and terminology. User-requested notation overrides the notes. Make every renaming consistent in the setup, derivations, hints, and code instructions.
- If the user specifies a working folder, treat its files as authoritative. Read them before editing; do not overwrite later changes with an older workspace copy. Keep the editable source and final PDF together there, with build intermediates elsewhere when practical.
- Do not invent a due date. Preserve supplied logistics and point totals unless the requested revision calls for changing them.

## Choose substantive questions

Lead each main question with a motivating question or concise description of its mathematical or statistical purpose. Keep required tasks clear while allowing alternative valid approaches; do not require narrow learning-outcome statements or disclose the solution method when choosing it is part of the task.

Prioritize short fundamental derivations that expose the statistical mechanism, and small numerical experiments that verify fundamental ideas, methods, or phenomena. Welcome explanation and visualization tasks that help students build intuition, especially when they connect a derivation to what the experiment shows. Keep the assignment concise and substantive: supply routine algebra and supporting identities, and remove mechanical repetition and low-value deliverables.

Use results already established in the lecture notes as tools rather than asking students to re-derive them. Supply the needed formulas or refer precisely to the relevant lecture result, then ask students to apply, compare, interpret, or check it computationally. Develop fundamental derivations through a concrete application, a special case, or a short consequence of lecture results; avoid repeating an existing lecture proof unless explicitly requested. Do not interpret this rule as a reason to remove all derivations or replace them entirely with verbal questions. Make each part advance the question and reuse earlier work. Where revealing, ask students to locate an assumption in a proof, construct a counterexample, diagnose a plausible error, or transfer an argument to a new setting; do not impose these on every question.

For a research extension, verify the source and identify the result or finding to investigate. Keep the question bounded, supply unfamiliar prerequisites, and distinguish established results from conjectures or proposed work. Judge the reasoning and evidence rather than requiring a successful novel result. Mark substantial extras optional unless assigned explicitly.

When a quiz or other workload constraint is mentioned:

- Keep only the derivations that teach the core techniques and a small number of interpretable checks.
- Supply already-covered posterior updates and supporting distribution formulas when deriving them is not the objective.
- Remove redundant proofs, multiple numerical scenarios, redundant plots, tail probabilities, quantiles, and MCSE calculations unless they are learning objectives themselves.
- Prefer one short simulation check per relevant question, with reusable code and data. Do not add computation automatically if the user has not requested it or it does not help.
- A two-question, two-page handout can be a useful target, not a constraint that justifies tiny text or crowded mathematics.

Split genuinely different techniques into separate questions when one question becomes unwieldy. Keep computation within its corresponding question rather than collecting it in a detached section. Reconcile all part labels, cross-references, instructions, and points after reorganizing.

Make background linear-algebra fact checking optional and ungraded by default (for example, trace identities, positive semidefiniteness, and Cholesky decomposition). Supply the needed identities and conditions for required statistical derivations so optional proofs are not hidden prerequisites. Keep the graded work focused on statistical updating, computation, and interpretation.
## Make setups and guidance precise

Clearly define observations, random variables, parameters, hyperparameters, and future observations. Distinguish fixed observed data from newly simulated values. In hierarchical models, distinguish a shared parameter from a latent quantity that varies between observations. If a distribution is both a population distribution and a prior for a latent signal, explain the two roles.

For new applications, give a short motivation, define the minimum model, and make each exercise build one ingredient of the final procedure. Do not jump from an identity to an algorithm without explaining what is observed, learned, and simulated. Distinguish an ideal population result from empirical fitting and an exact identity from an approximation.

Prefer the simplest setting that retains the message. For example, use a univariate model when vectors and matrices add notation but no essential insight. Introduce multivariate structure when it adds substantive insight.

### Derivation hints

Place each hint beside the specific task it supports. Make each hint contribute a distinct idea; remove repeated or substantially similar hints, including prose that merely repeats a sketch or the task instructions. When a technique has already been explained, use a brief cross-reference if needed rather than restating the same hint.

Keep guidance available for readers needing support; do not assume hints must fade on a schedule. Use a short diagnostic prompt or check when it helps expose a misconception without revealing the assessed result. Offer a viable route when needed, preserving alternative valid approaches and any intended discovery. For example:

- For completing the square, identify the integration variable, suggest matching quadratic and linear coefficients, and give the Gaussian integral identity.
- For a recognizable probability kernel, first exploit the fact that its normalized density integrates to one. Retain constants needed to identify the resulting distribution.
- If useful, sketch the direct calculus alternative with the substitution, differential, transformed limits, and named integral. Do not require two proofs of the same identity unless comparison is the objective.
- For a moment integral, explain how multiplying by the variable changes the kernel's shape and supply the necessary recurrence identity. State moment-existence conditions.
- When claiming a distribution is preserved, explain the distributional closure and required independence; matching means and variances alone generally does not establish a distribution. Distinguish conditional from marginal claims.

For Gaussian prediction, the reusable teaching sequence is: integrate the mean by completing the square; with unknown variance, reuse that result and integrate the inverse-gamma kernel. Emphasize that marginalization averages over posterior uncertainty. A plug-in value generally omits uncertainty. This is an example, not a required topic for every assignment.
## Make required actions impossible to miss

- Give each part a short descriptive heading and put its point value beside that heading.
- Highlight required action phrases: **derive**, **identify**, **compute**, **simulate**, **report**, and **interpret**, including requests after equations. Avoid bolding whole paragraphs.
- Separate provided assumptions, formulas, and hints from tasks. Hints should not silently add required deliverables.
- Use one clearly stated output for each action. Check that every requested result is represented in the instructions and point allocation.
- Attach optional material to a specific required question or subpart as preparation or a further exercise, and explain that connection briefly. Place it with the relevant question, not in a detached collection. Mark it explicitly as optional and ungraded unless requested otherwise. Supply any facts needed for required work so the optional activity never becomes a prerequisite.
- When asked to save material for later, remove it from the current handout and preserve it as a separately usable source/document. Ensure the current submission instructions do not still refer to it.
## Audit clarity, substance, and workload

Read the assignment as a student: check each part's purpose, available information, prerequisites, requested output, and guidance. Reconcile notation, conditioning, labels, references, and points. Check derivations against the notes; avoid repeating lecture proofs unless requested. Brevity must not make a task cryptic.

Judge workload by the number and difficulty of actions, not headings or page count. Remove repeated algebra, redundant checks and plots, and exhaustive reporting that adds little insight. Reuse earlier results, keep representative diagnostics, and preserve requested content. Split dense demands or simplify deliverables as appropriate. Check likely misconceptions and ways to recover without adding a mandatory rubric or feedback process.
