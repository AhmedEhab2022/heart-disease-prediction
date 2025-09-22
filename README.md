# Heart Disease Prediction Project

## Overview

This project aims to analyze, preprocess, and model the UCI Heart Disease dataset using supervised and unsupervised machine learning techniques. The workflow includes data cleaning, feature engineering, dimensionality reduction (PCA), feature selection, model training, evaluation, and hyperparameter tuning. The project is organized for reproducibility and ease of experimentation.

## Project Structure

```
Heart_Disease_Project/
│
├── data/                # Raw and processed datasets (CSV)
├── models/              # Saved model files (pkl)
├── notebooks/           # Jupyter notebooks for each analysis step
├── results/             # Model evaluation results and reports
├── requirements.txt     # Python dependencies
├── .gitignore           # Git ignore rules
└── README.md            # Project documentation
```

## Notebooks

- **01_data_preprocessing.ipynb**: Data loading, cleaning, encoding, and EDA
- **02_pca_analysis.ipynb**: Principal Component Analysis (PCA) for dimensionality reduction
- **03_feature_selection.ipynb**: Feature importance, RFE, and chi-square selection
- **04_supervised_learning.ipynb**: Training and evaluating supervised models (Logistic Regression, Decision Tree, Random Forest, SVM)
- **05_unsupervised_learning.ipynb**: Clustering and unsupervised analysis
- **06_hyperparameter_tuning.ipynb**: Model tuning and optimization

## Data

- The `data/` folder contains:
  - `heart_disease.csv`: Original dataset
  - `heart_disease_ohe.csv`: One-hot encoded data
  - `heart_disease_preprocessed.csv`: Cleaned and scaled data
  - `heart_disease_pca.csv`: PCA-transformed data
  - `heart_disease_selected_features.csv`: Data with selected features

## Models

- The `models/` folder contains trained model files in `.pkl` format for reproducibility and deployment.

## Results

- The `results/` folder contains evaluation metrics and model comparison reports in `.txt` format.

## Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AhmedEhab2022/heart-disease-prediction.git
   cd Heart_Disease_Project
   ```
2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch JupyterLab or Jupyter Notebook:
   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```

## Usage

- Open the notebooks in order for a step-by-step workflow, or jump to a specific analysis stage as needed.
- All intermediate and final datasets are saved in the `data/` folder for reuse.
- Trained models and results are available for further analysis or deployment.

## Requirements

See `requirements.txt` for all Python dependencies.

## Credits

- Dataset: [UCI Machine Learning Repository - Heart Disease Data Set](https://archive.ics.uci.edu/dataset/45/heart+disease)
- Developed by: [Your Name or Team]

## License

This project is licensed under the MIT License. See the LICENSE file for details.
