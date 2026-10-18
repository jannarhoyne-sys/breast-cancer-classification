# Breast Cancer Classification

Eight scikit-learn classifiers on the UCI Breast Cancer Wisconsin (Original) dataset
(683 patients after removing missing values; 75/25 stratified split, random_state=29).

Best model: Kernel SVM (RBF), 96.49% accuracy.

## Setup
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

## Files
- `*.py`: one script per model
- `notebooks/`: Jupyter notebooks with outputs
