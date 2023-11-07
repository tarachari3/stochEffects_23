# Stochastic Modeling of Biophysical Effects of Perturbations
Code and analysis for predicting perturbation-induced kinetic changes in single and combinatorial perturbation settings.
We use the Chemical Master Equation (CME) formalism to parametrize these biological systems.

Results presented at the 2023 CSHL Single Cell Analyses conference.

## Scripts Directory Contents

Scripts for downloading and processing raw fastqs to obtain unspliced and spliced RNA counts, for each dataset used.

To generate final loom counts files, run scripts in order: (1) fetch.sh --> (2) count.sh --> (3) concat.sh

## Metadata Directory Contents

Saved metadata for the datasets analyzed, used in the analysis notebooks (below).

## Notebooks Directory Contents

Notebooks for analyzing and processing germ cell development, Perturb-seq, drug screen, and drug resistance datasets.

Examples of meK-Means usage, for identifying cell populations with shared kinetics, can be found [here](https://github.com/pachterlab/CGP_2023).

All analyses used the [_Monod_ package](https://monod-examples.readthedocs.io/en/latest/) for CME inference from single-cell data. 
