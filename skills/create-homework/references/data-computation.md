# Create Homework: data computation

Apply these standards within the scope selected in [SKILL.md](../SKILL.md). This reference does not initiate a separate review pass or expand the task.

## Use data when it serves the question

Use simulated or accessible public data when empirical reasoning advances the question. Proofs, constructions, and counterexamples need no artificial dataset. Every supplied dataset should support a concrete task; reuse data across questions where useful. Sufficient statistics may replace raw observations when adequate for the analysis.

For simulated data, make each question self-contained: put the realized observations or their sufficient statistics directly in the handout, or include a short, complete generation recipe or code block there with the seed, model, and generating parameters. Do not require or provide a separate generation script or data file unless the user asks for one. For grouped data, prefer compact sufficient or summary statistics to long observation lists; choose enough groups to reveal the phenomenon. Include group identifiers and sample sizes; supply means and within-group sums of squares when variance is unknown, and the summaries required by the model when it is known. For nested models, identify each group and its parent. Define scatter versus covariance and all denominator conventions. Printing the observations or their sufficient statistics removes the need for generation code. Label simulated data clearly, distinguish any generating values from unknown inferential parameters, and keep the dataset fixed during posterior simulation. For public real data, verify access, cite a direct source link, define the variables and units, and document any subset or preprocessing. Supply a usable file when permitted, or clear retrieval instructions. Check that any supplied summaries agree with the actual data.

## Keep simulations small and purposeful

State the phenomenon and a meaningful comparison or benchmark without giving away an intended discovery. For repeated-sampling means, variance, bias, risk, or convergence, specify enough independent datasets and account for Monte Carlo uncertainty to support the comparison; distinguish this from fitting one dataset. Specify the generating model, parameters, seed, and outputs. Keep the observed dataset fixed for posterior-predictive simulation.

Write the sampling order explicitly. Preserve dependencies: when a variance is drawn for a replicate, reuse it in that replicate's conditional mean and future-observation draws. Distinguish normal variance from standard deviation, Gamma rate from scale, and Student-t scale from standard deviation.

Choose the representation that reveals the phenomenon: a calculation, compact table, or plot with interpretation. Require plots only when informative; specify axes, labels, and relevant references, or explicitly leave their choice to students. Add a guiding schematic only when it clarifies an unfamiliar display without revealing the central discovery. Label it schematic, identify its encodings, and avoid implying a required numerical shape. Reuse computations and allow standard random generators unless implementation is the purpose.

Check numerical inputs and benchmark results privately before delivery. Choose parameter values with the moments needed for the requested checks. Do not add a solution key to the student handout; create separate instructor solutions only when requested.
