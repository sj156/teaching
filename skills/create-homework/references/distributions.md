# Create Homework: distributions

Apply these standards within the scope selected in [SKILL.md](../SKILL.md). This reference does not initiate a separate review pass or expand the task.

## Distribution convention: Gamma uses shape and rate

Use the shape--rate parameterization throughout: $G\sim\operatorname{Gamma}(a,b)$ means shape $a>0$ and rate $b>0$, with density $b^a g^{a-1}e^{-bg}/\Gamma(a)$ for $g>0$, mean $a/b$, and variance $a/b^2$. State this convention wherever Gamma distributions enter an assignment. In software that accepts a scale, pass `scale=1/b`; keep the mathematical notation in shape--rate form. Check CDFs, quantiles, random generators, and reciprocal transformations against this convention.

Distinguish inverse-gamma explicitly: $V\sim\operatorname{InvGam}(a,b)$ has density $b^a v^{-(a+1)}e^{-b/v}/\Gamma(a)$, so $1/V\sim\operatorname{Gamma}(a,b)$ under the shape--rate convention. The inverse-gamma parameter $b$ is its scale and the reciprocal Gamma's rate; do not relabel the inverse-gamma parameter or change its density to impose Gamma terminology.
