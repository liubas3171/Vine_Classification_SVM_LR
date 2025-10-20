This repository presents the implementation and evaluation of machine learning algorithms
for wine quality prediction. The task is binary classification: predicting whether a wine
is “good” (quality ≥ 6) or “bad” (quality < 6) based on its chemical properties.
Was implemented two main classification algorithms from scratch:

- Logistic Regression using Online Gradient Descent
- Support Vector Machine (SVM) using the Pegasos algorithm

Additionally, both algorithms were extended using kernel methods to capture non-linear
relationships in the data. Two kernel functions were used: Gaussian and Polynomial.
