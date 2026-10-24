# Exercises

Apply within [SKILL.md](../SKILL.md)'s scope. These notes provide an exercise bank, not a single assignment.

## Purpose and coverage

- Every exercise should expose a **fundamental concept or meaningful distinction**. Identify what students should understand differently afterward: for example, estimation versus prediction, bias versus variance, fixed versus random design, exact reproduction versus stability, or a method's benefit versus its cost. Choose distinctions relevant to the lesson, not a mandatory checklist.
- Make computation serve that purpose. Ask students to compare assumptions or methods, explain a mechanism, interpret a failure, or justify a choice. Retain insightful derivations; supply routine identities and allow software when arithmetic is incidental. A final generic “interpret” prompt does not rescue a calculation-only task.
- Provide sufficient, varied numbered practice across the developed material, judged by conceptual coverage, depth, and workload rather than a fixed count per subsection. Review questions complement independent exercises. Preserve worthwhile practice and support readers needing guidance without limiting the depth of optional challenges.
- Mix interpretation, derivation, computation, and real-data work where relevant. Selectively ask readers to locate an assumption in a proof, construct a counterexample, diagnose an error, or transfer an argument. Do not force a template, dataset, or plot onto a theoretical question.

## Setup and placement

- Use the course's `exercise` environment, a concise title, a motivating question, and multipart tasks with defined inputs and outputs. Sequence target → analysis or computation → comparison → explanation; avoid redundant scenarios and excessive student workload.
- Synthetic-data examples must contain **at least five observations**, and usually substantially more when illustrating noise, irregular support, or empirical behavior. Five is a minimum, not a realism target. Specify the generating model, design, sample size, error law, and reproducibility settings needed to execute the task. Do not pad a tiny example by duplicating observations.
- Small symbolic matrices or algebraic counterexamples may isolate a mathematical identity; they are not substitutes for synthetic-data examples. Do not relabel a three- or four-observation dataset as an algebra exercise to evade the minimum.
- Place essential practice near its prerequisites, preserving definition–illustration and result–proof adjacency. Keep optional tangents out of an unfinished main argument; position them after that argument's conclusion and mark them skippable. Do not create exercise-only subsubsections or move the entire bank to the subsection's end.
- For investigations, specify varied factors, controls, recorded quantities, suitable displays, repetitions, and uncertainty enough for execution while preserving the discovery. Real-data tasks need an accessible source, variables, units, preparation, and substantive question; use [figures](figures.md) for EDA. Simulations do not replace relevant real-data investigations.

## Extensions and verification

- Scaffold unfamiliar extensions with definitions, construction rules, intermediate identities, and available hints; do not turn removed exposition into unexplained proof demands or assume a fixed progression toward independence. Preserve the central discovery and allow alternative valid approaches. Mark substantial extras optional and avoid assigning an untaught chapter. Research extensions need bounded questions and achievable stopping points; a justified negative finding can be valuable.
- Consolidate shared procedures while retaining distinctions between applications. For UQ, preserve pointwise versus simultaneous, smoothed versus population targets, and stochastic error versus bias. Create solutions or companions only when requested or established by course format.
- Synchronize exercises after changing examples or figures: designs, distributions, sample sizes, parameters, labels, and panel references. Explain intentional differences without solving the central task.
- Routine histograms, ECDFs, and scatterplots need no figure citation when self-contained. Complex visual constructions need a preceding worked figure, its actual reference, and the retained encodings and changed inputs. Distinguish descriptive plots from calibrated inference.
- Check motivation, prerequisites, quantities, meaningful outputs, notation, workload, part labels, references, and rendered placement. Use consistent emphasis. Review questions follow [exposition](exposition.md); optional extensions do not require additional subsection boxes.
