# IBM-Assignment
In this notebook we try to practice all the classification algorithms 

We load a dataset using Pandas library, and apply the following algorithms, and find the best one for this specific dataset by accuracy evaluation methods.
Here We use the training set to build an accurate model. Then use the test set to report the accuracy of the model we will use the following algorithm:

1-   K Nearest Neighbor(KNN)
2-   Decision Tree
3-   Support Vector Machine
4-   Logistic Regression

About the Dataset:
This dataset is about past loans. The Loan_train.csv data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

Field	Description
Loan_status-----	Whether a loan is paid off on in collection
Principal	Basic----- principal loan amount at the
Terms	Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule
Effective_date------	When the loan got originated and took effects
Due_date-----	Since it’s one-time payoff schedule, each loan has one single due date
Age-----	Age of applicant
Education----	Education of applicant
Gender-----	The gender of applicant
