# Machine learning for entanglement detection

Course material on training neural networks to tell entangled two-qubit states from separable ones.
Based on the bachelor's thesis (TFG) of J. Buenestado ([original repository](https://github.com/JBuenestado/TFG)).

## Notebooks

Open a notebook in Google Colab with its button. No installation is needed: the first cell downloads this repository.

| Notebook | What it does | Open |
| --- | --- | --- |
| `generate_quantum_states.ipynb` | Generates random pure and mixed two-qubit states and sorts them by negativity | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dmanzanodiosdado/EntanglementDetection_UIMP/blob/main/generate_quantum_states.ipynb) |

In Colab, use **Runtime → Run all**. Files you generate there are deleted when the session ends.

## Running on your own computer

```bash
git clone https://github.com/dmanzanodiosdado/EntanglementDetection_UIMP.git
cd EntanglementDetection_UIMP
python3 -m pip install numpy scipy pandas matplotlib notebook
python3 -m notebook
```

Start Jupyter from this folder (the repository root), so the notebooks find the code in `matrices/modules/`.

## Repository layout

See `README.txt` for the original description of the folders: `matrices/` and `feature/` (training with 32 matrix entries or 9 features), `results/`, `PLOTS/`.
