# CS_decomposition

A small repository containing a Jupyter notebook (`CS.ipynb`) that demonstrates and documents the core ideas, examples, and experiments for the "CS decomposition" work in this folder.

## Contents

- `CS.ipynb` — the primary Jupyter notebook with explanations, code cells, and visualizations.
- `README.md` — this file.

## Summary

This project is a focused exploration and implementation of the Cosine–Sine (CS) decomposition and its application to linear-optical systems. The notebook implements examples and experiments inspired by the paper:

"Implementation of discrete positive operator valued measures on linear optical systems using cosine-sine decomposition"
by Jaskaran Singh, Arvind, and Sandeep K. Goyal (Department of Physical Sciences, IISER Mohali).

The notebook contains:

- A brief theoretical introduction and motivation for applying the Cosine–Sine decomposition to linear-optical implementations of discrete POVMs
- Worked examples with code (NumPy / SciPy) that demonstrate the decomposition and small optical-circuit-style constructions
- Visualizations to illustrate results (matrix structures, singular values, reconstruction checks)
- Minimal reproducible experiments you can run locally



## Prerequisites

You will need Python 3.8+ and Jupyter. The notebook uses common scientific Python packages; a recommended list is below.

- numpy
- scipy
- matplotlib
- pandas (optional)
- scikit-learn (optional)
- jupyter

## Quick start (Windows / PowerShell)

1. Create and activate a virtual environment (recommended):

```powershell
python -m venv .venv; .\.venv\Scripts\Activate.ps1
```

2. Install the common dependencies:

```powershell
pip install --upgrade pip
pip install numpy scipy matplotlib pandas scikit-learn jupyter
```

3. Launch Jupyter and open the notebook:

```powershell
jupyter notebook
```

4. In the browser, open `CS.ipynb` and run the cells top-to-bottom.

Optional: export the notebook to HTML to share results:

```powershell
jupyter nbconvert --to html CS.ipynb
```

## What to look for in the notebook

- Explanatory sections that outline the mathematical idea behind the decomposition.
- Code cells that implement the decomposition and small helper functions.
- Plots showing data before and after decomposition and numerical checks (reconstruction error, orthogonality, etc.).



