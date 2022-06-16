This repository contains a Jupyter notebook demonstrating the use of Gibbs sampling
to performing interpolation of missing data described by an autoregressive model. This is based
on Chapter 6 of [_Numerical Bayesian Methods Applied to Signal Processing_](https://link.springer.com/book/10.1007/978-1-4612-0717-7) by J. Ó Ruanaidh & W. Fitzgerald.

The notebook can be run in a conda environment generated using the provided [`environment.yml`](environment.yml) file. E.g.,
Create the environment with:

```bash
conda env create -f environment.yml
```

and run the notebook with:

```bash
conda activate interp-autoreg
jupyter notebook interp-autoreg.ipynb &
```
