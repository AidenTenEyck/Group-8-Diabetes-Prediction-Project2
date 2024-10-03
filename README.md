The goal of this project is to narrow down and accurately predict people who are at high risk for diabetes by creating an algorithm using the diabetes prediction dataset. The dataset used has 100,000 rows and 9 columns. The data is medical in nature and includes details like whether the person has smoked, has heart disease, bmi, HbA1c level, blood glucose level, hypertension, and if they have diabetes. Overall the data appears to be unbalanced in most regards with very few people having heart disease, hypertension, or even diabetes.

We used five classifiers to analyze the data and train the model such as Logistic Regression, Random Forest, Decision Tree, Gradient Boosting, and KNeighborsClassifier. The model is more than 85% accurate using any of the above classifiers. The most accurate classifier is Random Forest which came in between 96-97% accuracy even when being undersampled or oversampled.  Some of the findings are that a higher level of HbA1c- and higher blood glucose levels can serve as a strong indicator of diabetes. There also appears to be some correlation between a person's age and if they have diabetes which could indicate that as you get older you have a higher chance of getting diabetes.

This algorithm could be used as an early warning system in a hospital to quickly narrow down patients who are at high risk for diabetes, or alternatively it could be used by medication companies by helping them narrow down their target audience to increase the effectiveness of advertisements for their products.
