# Machine learning model that predicts which employee is most at risk of having an accident at work

A company is concerned about potential risks to its employees due to work accidents that occurred in its production process. In this context, it decides to adopt an action plan whose main objective is to reduce the risk of accidents in its plants. As a first step, it decides to conduct an analysis to investigate the main factors that may contribute to the occurrence of this event.

### Libraries used:

- pandas
- numpy
- matplotlib
- sklearn

python: 3.10.4

I tested 3 machine learning models: 
- Logistic Regression
- Decision Tree
- Random Forest

### With some data manipulation and hyperparameter tunning i get this results

<strong>Logistic</strong>: 

precision 78%
f1        84%
accuracy  74%
AUC       66%

<strong>Decision Tree</strong>:

accuracy 73%
AUC      68%

<strong>RandomForest</strong>:

precision 79%
recal     94%
accuracy  77%
AUC       69%
