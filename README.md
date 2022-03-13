# Algorithmic_Trading_via_Machine_Learning

This Jupyter notebooks demonstrates the different ways machine learning models can be optimized or made differently by changing parameters or using a different kind of model, and how these differences may affect the result of a trading algorithm.
The notebook contains the creation of a basic trading algorithm along with the whole process of model, fit, predict, evaluate for SVM and Logistic Regression models for the scaled data.

Included is also an evaluation report of the models.

---

## Technologies

### Libraries:
* Pandas
* NumPy
* hvplot.pandas
* matplotlib.pyplot
* SVM from sklearn
* StandardScaler from sklearn.preprocessing
* DateOffset from pandas.tseries.offsets
* classification_report from sklearn.metrics
* LogisticRegression from sklearn.linear_model

The language of this notebook is Python on the Anaconda developement environment, worked upon on Jupyter Lab. The libraries used that come with Anaconda Python are Pandas, NumPy, matplotlib.pyplot, and sklearn.

HvPlot must be installed.

---

## Installation Guide

To install HvPlot, enter `conda install -c pyviz hvplot` into your terminal.

After, enter `conda list hvplot` to confirm installation of both.

---

## Usage

### Charts that compare the different models to the actual returns of their respective configurations:

#### First SVM Trail VS Actual Returns of Baseline Algorithm:

![Screenshot of original evaluation.](images/svm_trial_1.png)

#### Second SVM Trail VS Actual Returns of Baseline Algorithm:

![Screenshot of resampled evaluation.](images/svm_trial_2.png)

#### Third SVM Trail VS Actual Returns of Baseline Algorithm:

![Screenshot of original evaluation.](images/svm_trial_3.png)

#### Logistic Regression VS Actual Returns of Baseline Algorithm:

![Screenshot of original evaluation.](images/logreg_trial.png)

All info is already input and worked on within the Jupyter file. Simply start from the top and go down the page to view relevant data, calculations, analysis, and notes.

---

## Contributor

Isaiah T Tensae