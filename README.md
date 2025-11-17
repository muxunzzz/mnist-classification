# MNIST Classification

This Jupyter Notebook demonstrates how to train and evaluate a KNN Classifier and a Random Forest Classifier to classify handwritten digits from the MNIST dataset.

## Contents

- `MNIST Classification.ipynb`
  - Load the MNIST dataset.
  - Preprocess images and labels.
  - Define and train models (KNN Classifier and Random Forest Classifier).
  - Evaluate performance and show accuracy plots.

## Requirements

At minimum you need:

- Python 3.8+
- Jupyter Notebook / JupyterLab
- Usual utilities: `numpy`, `matplotlib`, `scikit-learn`

## Quick start

1. Clone the repository:

```bash
git clone https://github.com/muxunzzz/mnist-classification.git
cd mnist-classification
```

2. Open the notebook:

   JupyterLab or Jupyter Notebook

3. Run the notebook cells in order. The notebook downloads MNIST automatically (no manual dataset download required).

## Reproducibility tips

- Set a random seed in the notebook to make training deterministic where possible.
- Note that exact bitwise reproducibility may vary by platform, GPU, and backend.
