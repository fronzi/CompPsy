# PDNPD — precision-dysregulation model of narcissistic pathology

`npd_simulation.ipynb` simulates an agent inferring another's mental state
through a cognitive stream (Bayesian posterior mean) and an affective stream
whose integration is gated by the precision of a self-referential feedback
channel. Empathy accuracy and concern are computed from the two streams;
threat accumulation drives precision decay.

Functions: `make_stim_sequence`, `simulate_agent`, `run_ensemble`,
`scalar_summary`, `mwu` (Mann–Whitney U comparison), `double_well`
(phase-portrait potential). Figures `fig1`–`fig5` are written next to the notebook.
