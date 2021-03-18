# Employee_Attrition_Prediction

Problem Statement
Uncover the factors that lead to employee attrition and explore important questions leading to attrition. This is a fictional data set created by IBM data scientists.

Your aim is to predict the Attrition of the employee.

About the Dataset:
Snapshot of the data you will be working on:

DT&ET_image

This is a highly imbalanced dataset. For this task, we have already applied an oversampling technique to deal with this.

A zipped file containing the following items is given:

train.csv :
The data file train.csv contains the 1281 instances with the 35 features including the target feature.




test.csv" :
The datafile test.csv contains the 321instances with the 34 features excluding the target feature.




sample_submission.csv :
Explained under the Submission sub-heading




DataDictionary.csv:
The file contains data dictionary(Dictionary explaining what each feature of the dataset means) of the dataset




Employee_Attrition_student_template.ipynb :
A template notebook explaining the task breakdown to solve the given problem statement (Learners are recommended to use it)

Submission
After training the model on train.csv data, the learner has to predict the target feature of the test.csv data using the trained model. The learner has to then submit a csv file with the predicted feature.

Sample submission file(sample_submission.csv) is given to you as a reference to the format expected when you submit

Evaluation metrics
For this particular dataset we are using roc_auc_score as the evaluation metric.

Submissions will be evaluated based on roc_auc_score

Your roc_auc_score score	Points earned for the Task
roc_auc_score>= 0.70	100% of the available points
0.67 =< roc_auc_score < 0.70	80% of the available points
0.64 < roc_auc_score < 0.67	70% of the available points
roc_auc_score <= 0.64	No points earned
Outcomes
The main objective of this task is to provide you with an open field where you can practice and work your way with a dataset end to end without any restrictions from our side. So feel free to play around the model until you arrive at your best solution.

In this project, you will apply the following concepts:

Train-test split
Correlation between the features
Decision Trees & Ensemble Techniques
ROC-AUC Score


After completing this project, you will have a better understanding of how to use Ensembling Techniques.

Skills Covered:
data cleaning
Ensemble Methods
GBM
correlation plot
