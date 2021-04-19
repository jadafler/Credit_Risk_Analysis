# Credit_Risk_Analysis
Module 17

## Overview of Project
Loans are an essential program for a variety of required and desired items, experiences, education, etc. In this analysis, we can use collected data to predict a credit risk based on a variety of attributes such as the amount of the loan, annual income, interest rate, debt flagging, and much more. This will assist in assessing the risk to maximize the repayment status for a borrower. We will use Machine Supervised Learning since the data attributes and outcome are known and a random forest classifier for our prediction model. 

## Results
The data collected from current loans offer a variety of attributes to train, test, and predict with:
<br>
<i>Loan Amount, Interest Rate, Installment Payment, Home Ownership Status, Annual Income, Verification Status, Issue Date, Risk Value, Payment Plan Status, Hardship Flag, Debt Settlement Flag, along with moneterary amounts for the loan. </b>

<b>Descriptive statistics regarding the dataframe:</i>

<img src="Images/df.describe.png" alt="df.describe"> 

<br>
<br>

<b><i>The Balanced Accuracy Score</i></b> provides the average of the accuracy per class. Additionally, the <b><i>Precision</i></b> and <b><i>Recall</i></b> returns from the  Confusion Matrix will provide the following analysis: the precision will measure whether the prediction is represented strongly when evaluating the data. The recall will reflect the how well the predication determined the outcome.  

<br>
<br>

<li><b>Cluster Centroids Resampler Classification Report, Balanced Accuracy Score = 54%</b></li>
<img src="Images/CCR_report.png" alt="Cluster Centroids Resampler Classification Report">

<br>

<li><b>SMOTEENN Classification Report, Balanced Accuracy Score = 66%</b></li>
<img src="Images/smoteenn_report.png" alt="SMOTEENN Classification Report">

<br>

<li><b>SMOTE Classification Report, Balanced Accuracy Score = 66%</b></li>
<img src="Images/smote_report.png" alt="SMOTE Classification Report">

<br>

<li><b>Random Over Sampler Classification Report, Balanced Accuracy Score = 67%</b></li>
<img src="Images/ROS_report.png" alt="Random Over Sampler Classification Report">

<br>

<li><b>Random Forest Classification Report, Balanced Accuracy Score = 79%</b></li>
<img src="Images/RFC_report.png" alt="Random Forest Classifier Classification Report">

<br>

<li><b>Easy Ensemble Classifier Classification Report, Balanced Accuracy Score = 93%</b></li>
<img src="Images/EEC_report.png" alt="Easy Ensemble Classifier Classification Report">

