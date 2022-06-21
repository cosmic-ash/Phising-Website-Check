# Phising-Website-Check

A logistic regression model that classifies if a website is phising website or not.

The dataset consists of 30 features and total record count is 2456.

In the notebook I read the data, look at which features can give us information about what are the features of an phising website.

To find non-linear and linear correlation between features and label I have used multual info classifier.

The logistic regression model is trained repitatively. The fucntion takes top N features which are used to train the model. The number of features varies from 10 to 30. This is done to see the optimum number of features that can be used to find the best fittest logistic regression model.
Evaluation metrics used are accuracy, precision, recall and f1 score.
