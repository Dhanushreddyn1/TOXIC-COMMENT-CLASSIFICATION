# Toxic Comment Classification

This repository contains the data and notebook for a toxic comment classification project.

Contents
- `Comment Toxicity Model - 16.ipynb` — Jupyter notebook with model experiments and training.
- `train.csv`, `test.csv`, `test_labels.csv` — dataset files (training, test, labels).
- `glove.840B.300d.txt` — pre-trained GloVe embeddings used for embedding layer.
- `sample_submission.csv`, `results.csv` — submission and results files.

Quick start
1. Open the notebook `Comment Toxicity Model - 16.ipynb` in Jupyter or VS Code.
2. Install required Python packages (example):

```
python -m pip install -r requirements.txt
```

If you don't have `requirements.txt`, install common libraries used for the project:

```
python -m pip install numpy pandas scikit-learn matplotlib seaborn jupyter notebook tensorflow keras
```

Notes
- The notebook uses pre-trained GloVe vectors (`glove.840B.300d.txt`) — loading them can take time and memory.
- Adjust dataset paths in the notebook if you move files.

Git
- To add and push this README:

```
git add README.md
git commit -m "Add README"
git push
```

License
- Add license information here if desired.

Contact
- For questions, edit this README or open an issue in the repo.
