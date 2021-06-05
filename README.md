# Stroke-EDA-Predictor

## Introduction

This is a stroke prediction script written for our Machine Learning final project. The dataset was obtained
from [Kaggle](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).

## Getting Started

### Prerequisites

The following dependencies are required:<br/>

* numpy
* pandas
* math
* seaborn
* matplotlib
    * pyplot
* sklearn
    * model_selection
    * preprocessing
    * utils
    * metrics
    * svm
* imblearn
    * over_sampling

If using Anaconda with Python 3.8+, everything above is included except `imblearn`. To add this, run:

```bash
conda install -c conda-forge imbalanced-learn
```

Else, individually install these libraries using `pip install`.

### Running The Notebooks

Given the `.idea` folder, the project can be set up in PyCharm Professional. However, using other IDEs such as Jupyter
Notebook or JupyterLab will also suffice.

## Contributions

|        Author        |                      File                       |
| :------------------: | :---------------------------------------------: |
| Chathumini Abeyratna | [Logistic Regression](LogisticRegression.ipynb) |
| Saadiya Allahbaksh   | [SVM](SVM.ipynb)                                |
| Kevin Karnani        | [RandomForest]()                                |