# Breast Cancer Classification

A machine learning notebook that classifies breast tumors as **malignant** or **benign** using logistic regression on the Wisconsin Breast Cancer Diagnostic dataset from scikit-learn.

## Features

- **Data preparation** — Loads and preprocesses the built-in `load_breast_cancer()` dataset with pandas
- **Model training** — Logistic regression for binary classification
- **Evaluation** — Reports accuracy on training and held-out test splits

## Tech Stack

| Component | Technology |
|-----------|------------|
| Language | Python 3.x |
| Libraries | NumPy, pandas, scikit-learn |
| Environment | Jupyter Notebook |

## Project Structure

```
Breast-Cancer-Classification/
├── Breast_Cancer_Classification.ipynb   # Full pipeline: EDA, train, evaluate
├── requirements.txt
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

```bash
git clone https://github.com/priyqnk/Breast-Cancer-Classification.git
cd Breast-Cancer-Classification

pip install -r requirements.txt
```

### Usage

```bash
jupyter notebook Breast_Cancer_Classification.ipynb
```

Run all cells to train the model and view accuracy metrics.

## Results

Logistic regression on an 80/20 train–test split (default `random_state` in the notebook):

| Split | Accuracy |
|-------|----------|
| Training | **94.9%** (0.949) |
| Test | **93.0%** (0.930) |

## Dataset

The [Wisconsin Breast Cancer Diagnostic dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) provides 30 numeric features derived from digitized fine needle aspirate images. Labels indicate malignant (`0`) or benign (`1`) diagnosis.
