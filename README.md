# 📊 A Voting Classifier on Breast Cancer Data and Random Forest on LFW

This repository demonstrates practical machine learning ensemble and classification techniques on two benchmark datasets.

## Table of Contents

* [Project Overview](#project-overview)
* [Data](#data)
* [How to Run](#how-to-run)
* [Tech Stack](#tech-stack)
* [References](#references)

---

## Project Overview

* **Voting Classifier on the Wisconsin Breast Cancer Dataset**
  Implements an ensemble classifier combining Logistic Regression, Random Forest, and Support Vector Machine (SVM) using majority voting to improve diagnostic accuracy for breast cancer. Includes preprocessing, feature selection, model comparison, cross-validation, ROC analysis, and feature importance interpretation.

* **Random Forest on Labeled Faces in the Wild (LFW) Dataset**
  Applies Random Forest classification to facial recognition using the LFW dataset. Incorporates PCA for dimensionality reduction, hyperparameter tuning, and model evaluation.

---

## Data

* **Wisconsin Breast Cancer Dataset**

  * Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
  * Files: [`wdbc.names`](./wdbc.names), [`wdbc.data`](./wdbc.data)
  * Content: 569 instances, 32 attributes (ID, diagnosis, and 30 numerical features)

* **Labeled Faces in the Wild (LFW) Dataset**

  * Source: [LFW Official Site](http://vis-www.cs.umass.edu/lfw/)
  * Download via: [`sklearn.datasets.fetch_lfw_people`](https://scikit-learn.org/stable/datasets/real_world.html#labeled-faces-in-the-wild)

---

## How to Run

1. Clone this repository.
2. Open and run the Jupyter notebook:
   [`A Voting Classifier on Breast Cancer Data and Random Forest on LFW.ipynb`](./A%20Voting%20Classifier%20on%20Breast%20Cancer%20Data%20and%20Random%20Forest%20on%20LFW.ipynb)
3. Ensure you have the required Python packages:

   * `scikit-learn`
   * `pandas`
   * `numpy`
   * `matplotlib`
   * `seaborn`
4. Download the dataset files ([`wdbc.data`](./wdbc.data), [`wdbc.names`](./wdbc.names)) into the working directory (if not already present).

---

## Tech Stack

* Python (Jupyter Notebook)
* scikit-learn
* pandas, numpy
* matplotlib, seaborn

---

## References

* Dua, D. and Graff, C. (2019). [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml). Irvine, CA: University of California, School of Information and Computer Science.
* [Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/)

