# Tutorial Modeling Data Titanic

Tutorial ini akan mengolah data titanic menjadi data yang siap untuk dilakukan pemodelan

## Prerequsites

1. Download data [here](https://www.kaggle.com/datasets/brendan45774/test-file)
2. Instalasi dengan `pip install requirements.txt`

## Getting Started

- Dataset Splitting
- Training
- Model Validation

### Dataset Splitting

Split data into training, validation and test sets
```code
X_train, y_train, X_test, y_test = dataset_splitting()
X_train.shape, y_train.shape
```

## References:

1. Di scikit-learn documentation