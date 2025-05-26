# CLEXNET – Synthetic-Data Tutorial Notebook  🤖 🧪

This repository contains an interactive Jupyter notebook that walks you through

* generating a **synthetic organ–offer dataset**—complete with
  * patient covariates **`X`** (confounders),
  * organ features **`O`** (treatment),
  * binary acceptance label **`y`**, and
  * direction-only refusal reasons **`dX`, `dO`**;
* training an **sklearn-compatible** implementation of **CLEXNET** on the biased
  observational split;  
* evaluating generalisation on an unbiased RCT-like hold-out set.
