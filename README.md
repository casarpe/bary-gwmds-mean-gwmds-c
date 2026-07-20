# GW Multi-View Embedding and Clustering

Experimental code associated with the paper
“Gromov-Wasserstein Methods for Multi-View Relational Embedding
and Clustering,” accepted at SBrT 2026.

## Experiments

- `bary_gwmds_experiments.py`: Bary-GWMDS experiments.
- `mean_gwmds_c_experiments.py`: Mean-GWMDS-C experiments.

## Installation

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
