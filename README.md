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

<br><strong>Logistic</strong>:</br> 

precision 78%<br></br>
f1        84%<br></br>
accuracy  74%<br></br>
AUC       66%

<br><strong>Decision Tree</strong>:</br>

accuracy 73%<br></br>
AUC      68%

<br><strong>RandomForest</strong>:</br>

precision 79%<br></br>
recal     94%<br></br>
accuracy  77%<br></br>
AUC       69%
