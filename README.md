# GW Multi-View Embedding and Clustering

Experimental code associated with the paper
“Gromov-Wasserstein Methods for Multi-View Relational Embedding
and Clustering,” accepted at SBrT 2026.

The repository provides Python scripts and Google Colab notebooks
for Bary-GWMDS and Mean-GWMDS-C.

## Experiments

### Python scripts

- [`bary_gwmds_experiments.py`](bary_gwmds_experiments.py): Bary-GWMDS experiments.
- [`mean_gwmds_c_experiments.py`](mean_gwmds_c_experiments.py): Mean-GWMDS-C experiments.

### Colab notebooks

- [`Bary_GWMDS_experiments.ipynb`](Bary_GWMDS_experiments.ipynb): executable Bary-GWMDS notebook.
- [`Mean_GWMDS_C_experiments.ipynb`](Mean_GWMDS_C_experiments.ipynb): executable Mean-GWMDS-C notebook.

The notebooks are the recommended option for reproducing the
experiments and can be opened directly with Google Colab.

## Installation

For local execution, install the required dependencies with:

```bash
pip install -r requirements.txt
```

## Execution

```bash
python bary_gwmds_experiments.py
python mean_gwmds_c_experiments.py
```

## Dependencies

The experiments require Python, NumPy, SciPy, PyTorch,
scikit-learn, POT, mvlearn, Matplotlib, and tqdm.
