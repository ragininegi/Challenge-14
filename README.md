# Algorithmic Trading Bot

An algorithmic trading bot that learns and adapts to new data and evolving markets using machine learning and financial python programming.

---

## Technologies:

It supports Python 3.7 and has been constructed using jupyter lab notebook.

Additionally, the following packages/libraries are used to run the analysis:

- pandas- for analyzing data
- numpy- for numerical operations
- hvplot - for visualizing data
- sklearn - for building machine learning models
- matplotlib - for creating plots
- pathlib - for creating objected oriented file modules

---


## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install pandas 
  pip install jupyter lab
  pip install numpy
  pip install sci-kit learn
  pip instal pathlib
  pip install hvplot

```

--- 

## Evaluation Report

- SVM classification report
![svm](https://github.com/ragininegi/Challenge-14/blob/main/Images/SVM%20classification.png)

- Return comparision of SMA vs Actual
![SVM_2](https://github.com/ragininegi/Challenge-14/blob/main/Images/SVM%20vs%20actual%20.png)

`Insights: The returns prediction did not improve when the training dataset size was increased. As the training set data increased, the precision and recall values for class -1 increased, whereas those for class 1 fell in comparison to the initial training dataset. The precision and recall increased when the brief window for SMA was increased. These scores rise up to a certain point, after which they start to fall. When we increase the long window while also extending the short window, we can get the best possible outcomes.`

- Logistic Regression classification report
![LR](https://github.com/ragininegi/Challenge-14/blob/main/Images/LR_classification.png)

- Logistic Regression returns vs Actual returns
![LR_2](https://github.com/ragininegi/Challenge-14/blob/main/Images/LR%20vs%20Actual.png)

`Insights: The logistic regression model is chosen as the new classifier after being backtested to assess its performance. We fitted the logistic regression model using the initial training data. Although this new model performed well, it fell short of our optimized trading method.`


---


## Contributors
 
Ragini Negi  
Email : negiragini16@gmail.com <br>
LinkedIn : https://www.linkedin.com/in/ragininegi/

---

## License

Apache License 2.0

---
