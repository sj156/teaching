# Notation

Apply within [SKILL.md](../SKILL.md)'s scope, by mathematical role throughout definitions, proofs, examples, exercises, algorithms, figures, and requested companions. Do not mechanically replace symbols or expand a skill-only edit into lecture revisions.

## Equations

Use inline math by default, including routine substitutions, values, short conditions, and ancillary notation. Display central definitions, constructions, results, consequential comparisons, or aligned derivations when emphasis or readability warrants it. Do not fragment sentences into isolated displays. Preserve labels/references and inspect rendered lines for crowding.

## Statistical conventions

- Complete data vectors: $\mathbf y=(y_1,\ldots,y_n)^\top$, with random counterpart $\mathbf Y$. Briefly state this convention at first use and give dimensions/sample size. Avoid redundant sample-size superscripts such as $\mathbf y^n$; preserve actual powers, sample-size notation for unbolded sequences, and meaningful draw/iteration indices such as $\mathbf Y_{\mathrm{rep}}^{(s)}$. Apply consistently to fitted and replicated vectors.
- Bold vectors and matrices using existing course commands: `\mathbf` for Roman letters and `\boldsymbol` or equivalent for Greek. Preserve role/case, e.g. $\mathbf X$, $\mathbf x$, $\boldsymbol\theta$. **Exception: matrix parameter $\Sigma$ remains ordinary.** Scalars and scalar entries remain unbolded.
- Uppercase Roman letters denote random variables; lowercase denote realizations ($X_i,x_i$). “Roman” means Latin letters, not upright type. Preserve regression/observation errors $\varepsilon_i$ and their vector/matrix $\boldsymbol\varepsilon$, plus established state-space innovation symbols. Distinguish unobserved errors from fitted residuals $e_i=y_i-\widehat y_i$. Do not rename expectation operators, exposure variables, or unrelated uses of a letter.
- Model parameters, parameter blocks, binary parameters, and prior/posterior draws use Greek letters, including Bayesian uncertain parameters. Do not rename them $A,B$ to state a sampling theorem: use $p(\theta,\phi\mid\mathbf y)$ and $(\theta^{(s)},\phi^{(s)})$. Reserve Roman uppercase/lowercase pairs for sampling variables/realizations.
- Prior hyperparameters use lowercase Roman letters with subscript $0$ ($m_0,a_0,b_0$); conjugate updates retain the base letter with subscript $n$ ($m_n,a_n,b_n$). Define sample size $n$ and parameterization; $0$ denotes the pre-data state.
- Apply conventions implicitly, except the brief complete-vector introduction above. Define objects and parameterizations where needed; give a concise mathematical bridge to earlier differing notation only when necessary. Keep editorial policy, symbol-renaming tutorials, and unnecessary alias tables out of student notes. Explanations never compensate for inconsistent formulas.
