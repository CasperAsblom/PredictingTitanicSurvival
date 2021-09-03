# PredictingTitanicSurvival

## Introduction
This project was part of the Machine Learning course at Vrije Universiteit Amsterdam. In the course, we were taught the basic principles, methodology, and algorithms of machine learning.

As a final project, we were to write a 10-page report in which we present a specific research question around some machine learning task, implementing one or more algorithms, and properly analyze the results. I chose to write a report named "Predicting survival on the Titanic with Machine Learning models", using data from the Kaggle competition "Titanic - Machine Learning from Disaster". In this report, I implemented and evaluated five machine learning algorithms (Random Forest, kNN, Stochastic Gradient Descent, Logistic Regression, and Support Vector Machines) to see which of them would perform the best in predicting which passengers survived the Titanic shipwreck. 

## Evaluation

All algorithms were tested on the given dataset, which was already split into approximately 70% training data and 30% test data. The performance of all models was estimated using 10-fold cross validation. The evaluation considered the precision, recall, and F-score for each algorithm, as well as their respective confusion matrix. In my implementation, the Random Forest algorithm outperformed the other algorithms in every aspect, with an average accuracy of 81.59% (+- 2.45%).

## Screenshots

Average accuracy error bars:  
![ResultsDEMO](https://user-images.githubusercontent.com/30833034/126154238-7c373daa-4c5a-4ecb-8b5c-6b47be90578f.png)
Precision, recall, and F-score:  
![PrecisionRecallF-score](https://user-images.githubusercontent.com/30833034/132021535-661a48fb-2747-4aad-a8c9-de288b68d862.png)
Random Forest confusion matrix:  
![RandomForestConfusionMatrix](https://user-images.githubusercontent.com/30833034/132021540-c39c85b6-0b4b-44ba-a061-264daf2b602d.png)

## Files
"PredictingTitanicSurvival.ipynb" is the notebook which you can run yourself, and which uses "test.csv" and "train.csv" as input.

"PredictingTitanicSurvivalNotebookPDF.pdf" is simply a PDF of the notebook, and "PredictingTitanicSurvivalReport.pdf" is the final report I handed in for the course, which does not showcase any code but is more theoretically detailed, containing descriptions of the algorithms along with references.



