# CompPsy — computational psychiatry simulations

Simulation code for a side line of research applying Bayesian generative
modelling (active inference, hierarchical precision-weighted prediction error)
to personality pathology. Each folder is a self-contained notebook that
defines the agents, runs an ensemble of simulations and produces the figures.

| Folder | Model | Output |
|---|---|---|
| [`HISD/`](HISD/) | Hierarchical Interoceptive–Social Inference Dysregulation. A healthy-control agent (hierarchical Gaussian gradient descent) and a BPD agent (suppressed interoceptive precision, bimodal social prior with Bayesian mixture updating) face the same three-state social paradigm (neutral / accept / threat). Measures recovery times and the belief landscape. | `pics/hisid_results.*`, `pics/hisid_landscape.*` |
| [`PDNPD/`](PDNPD/) | Precision-dysregulation model of narcissistic pathology. Cognitive and affective streams infer another agent's mental state; the self-referential feedback precision controls the dissociation between cognitive and affective empathy and the self-esteem dynamics. Includes ensemble statistics, a phase portrait and a sensitivity sweep. | `fig1`–`fig5` |

## Publication

The HISD model is described in

> M. Fronzi, "Hierarchical Interoceptive–Social Inference Dysregulation: A
> Computational Psychiatry Framework for Borderline Personality Disorder with
> Level-1 Active Inference Simulation and Implications for Cluster B Pathology",
> *Cognitive Computation* (accepted, 2026).

## Requirements

```bash
pip install numpy scipy matplotlib jupyter
```

Run each notebook top to bottom; figures are written next to the notebook.

## Author

Marco Fronzi, School of Physics, The University of Sydney — marco.fronzi@sydney.edu.au
