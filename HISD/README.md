# HISD — Hierarchical Interoceptive–Social Inference Dysregulation

`hisid_model.ipynb` implements two agents on a three-state Markov social
paradigm (neutral, accept, threat):

- `HCAgent`: healthy control, hierarchical Gaussian belief updating by gradient descent on precision-weighted prediction errors.
- `BPDAgent`: suppressed interoceptive precision coupled to a bimodal (split) level-2 social prior, updated as a Bayesian mixture; threat detection uses boosted precision.

Functions: `make_paradigm`, `run_sim`, `recovery_times`, `ensemble`,
`figure_main`, `figure_landscape`. Figures are saved to `pics/`.

See the repository README for the associated publication.
