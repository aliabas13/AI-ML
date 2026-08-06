# CSE364C — Artificial Intelligence and Machine Learning Lab

Lab practicals for the AI/ML course.

## Experiments

| Lab  | Experiment | Description | Key Libraries |
|------|-----------|-------------|---------------|
| Lab01 | Linear Regression for House Price Prediction | Predict California housing prices | scikit-learn |
| Lab02 | Linear Regression for Heart Disease Prediction | Predict heart disease presence (`heart.csv`) | scikit-learn, pandas |
| Lab03 | Logistic Regression on Diabetes Dataset | Classify diabetes outcome (`diabetes.csv`) | scikit-learn, pandas |
| Lab04 | Support Vector Classifier on Breast Cancer Dataset | Classify benign/malignant tumors | scikit-learn |
| Lab05 | Naive Bayes on MNIST Dataset | Digit classification | scikit-learn |
| Lab06 | KNN on IRIS Dataset | Iris species classification | scikit-learn |
| Lab07 | Feed Forward Neural Network on MNIST Dataset | Digit classification | TensorFlow/Keras |
| Lab08 | Feed Forward Neural Network on Fashion-MNIST Dataset | Clothing classification | TensorFlow/Keras |
| Lab09 | Feed Forward Neural Network on CIFAR-10 Dataset | Image classification | TensorFlow/Keras |
| Lab10 | Decision Tree for Fraud Detection | Credit card fraud detection (`creditcard.csv`) | scikit-learn, pandas |

## Folder Structure

```
CSE364C Artificial Intelligence and Machine Learning Lab/
├── Lab01/  house_price_prediction.py
├── Lab02/  heart_disease_prediction.py
├── Lab03/  logistic_regression_diabetes.py
├── Lab04/  svc_breast_cancer.py
├── Lab05/  naive_bayes_mnist.py
├── Lab06/  knn_iris.py
├── Lab07/  ffnn_mnist.py
├── Lab08/  ffnn_fmnist.py
├── Lab09/  ffnn_cifar10.py
├── Lab10/  decision_tree_fraud_detection.py
├── README.md
└── requirements.txt
```

## Datasets

Most experiments use datasets bundled with the libraries (California housing, Breast Cancer, MNIST, IRIS, Fashion-MNIST, CIFAR-10) and load automatically.

The following datasets are **not included** in this repo and need to be downloaded separately:

- **heart.csv** (Lab02) — [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease) or [Kaggle: Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **diabetes.csv** (Lab03) — [Kaggle: Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **creditcard.csv** (Lab10) — [Kaggle: Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Place the downloaded CSV files in the same folder as the corresponding script before running.

## Getting Started

```bash
pip install -r requirements.txt
python Lab01/house_price_prediction.py
```

> Lab07–Lab09 require TensorFlow; Lab02, Lab03, and Lab10 require the CSV files noted above.

## Requirements

- Python 3.8+
- numpy, pandas, scikit-learn, matplotlib, tensorflow
