 # Problem Statement

Prediction of bankruptcy is a phenomenon of increasing interest to firms who stand to loose money because on unpaid debts. Since computers can store huge dataset pertaining to bankruptcy making accurate predictions from them before hand is becoming important.
The data were collected from the Taiwan Economic Journal for the years 1999 to 2009. Company bankruptcy was defined based on the business regulations of the Taiwan Stock Exchange.
The main objective of this project is to use various classification algorithms on bankruptcy dataset to predict bankruptcies with satisfying accuracies long before the actual event.

# Number of Data
Number of instances: 6819
Number of attributes: 96

# Project Workflow

Importing Libraries

Loading the Dataset

EDA on features

Data Modeling

Comparison of Models

Feature selection

Conclusion

# Conclusion
The number of organizations that have gone bankrupt in 10 years between 1999 – 2000 is few.

An organization cannot guarantee not being bankrupt, although owning several assets.

Several companies possess many assets, which is always a good sign for an organization.

Most of the organizations in the dataset are running into losses for the past two years as their net income poses to be negative.

An increase in the values of the attributes “Debt Ratio %, Current Liability To Assets, Current Liability To Current Assets” causes an organization to suffer heavy losses, thus resulting in bankruptcy.
It is observed that “Debt Ratio %, Current Liability To Assets, Current Liability To Current Assets" attributes are a few of the attributes that have a high correlation with the target attribute.
Very few of the organizations that have had negative income in the past two years suffer from bankruptcy.

An increase in the values of the attributes that have a negative correlation with the target attribute helps an organization avoid bankruptcy.

There seems to be a relation between attributes that have a high correlation with the target attribute and a low correlation with the target attribute.

Random Forest Classifier and K Nearest Neighbour Algorithms gives the highest accuracy of 98%.
