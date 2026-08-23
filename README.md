# The Exact Temperature of Exponential-Weight Aggregation

## Abstract

The aggregate with exponential weights is a basic model-selection procedure whose behavior under random-design squared loss has resisted a sharp characterization. It is known to be suboptimal in expectation at sufficiently low constant temperatures, while a recent result proves the optimal excess-risk rate at temperature $T\geq4b^2$ when labels and predictions lie in $[0,b]$. We close the constant gap. For every fixed $T<4b^2$, we construct a fixed two-element dictionary and bounded random-design regression problems on which the expected excess risk is $\Omega(b^2/\sqrt n)$. The minimax two-model aggregation rate is $\Theta(b^2/n)$. Thus $4b^2$ is the exact inclusive threshold for uniform expectation-rate optimality. The same threshold governs every fixed full-support prior on two experts, while arbitrary priors receive oracle remainder $T\log(1/\pi_j)/(n+1)$ above it. The construction uses two nearly parallel experts whose loss difference has variance almost $4b^2$ times their squared separation. A local binomial limit resolves the competition between erroneous model selection and the curvature gain from averaging. The same constant is also necessary and sufficient for the deterministic exponential-tilting inequality behind the recent upper bound. The threshold is therefore statistical and analytic, rather than an artifact of either proof.

## Contributions

- an exact phase theorem: unaveraged AEW is uniformly expectation-rate optimal if and only if $T\geq4b^2$
- an $\Omega(b^2/\sqrt n)$ lower bound below the threshold using only two deterministic experts and a two-point input space
- a prior-dependent upper bound for arbitrary priors and the same exact threshold for every fixed two-expert prior
- a local-limit formula separating wrong-model cost from the negative curvature gain of aggregation
- a proof that $4b^2$ is also the exact threshold for the squared-loss tilting inequality used in the high-temperature analysis

This question is specific to the unaveraged random-design aggregate. Fixed-design exponential weighting has sharp oracle inequalities under noise assumptions. Progressive mixtures and localized online-to-batch aggregates average across sample sizes. Q-aggregation uses a different objective. None determines the temperature studied here.

## Keywords

exponential weights, aggregation, model selection, random design regression, excess risk, temperature threshold, lower bounds

## Files

- source: `aistats2027.sty`, `main_2026-08-12.tex`, `references.bib`, `supplement_2026-08-12.tex`.
- also: `main_2026-08-12.bbl`, `main_2026-08-12.pdf`, `supplement_2026-08-12.bbl`, `supplement_2026-08-12.pdf`.
