# logistic regression
Data Preprocessing Project – Imbalanced Classes Problem
Imbalanced classes is one of the major problems in machine learning. In this data preprocessing project, I discuss the imbalanced classes problem. Also, I discuss various approaches to deal with this imbalanced classes problem.

The imbalanced dataset in real-world problems is not so rare. In layman terms, an imbalanced dataset is a dataset where classes are distributed unequally. An imbalanced data can create problems in the classification task. Before delving into the handling of imbalanced data, we should know the issues that an imbalanced dataset can create.
The problem of imbalanced classes arises when one set of classes dominate over another set of classes. The former is called majority class while the latter is called minority class. It causes the machine learning model to be more biased towards majority class. It causes poor classification of minority classes. Hence, this problem throw the question of "accuracy" out of question. This is a very common problem in machine learning where we have datasets with a disproportionate ratio of observations in each class.
Eg.As the disease is extremely rare, so there are only 1% of patient who actually have the disease as compared to 99% patients who don’t have the disease. Our classifier returns high level of accuracy simply by returning "No Disease" to every new patient. But the classifier does not fulfil our goal of detecting patients with the rare disease. Hence, it is meaningless. This is an example of the imbalanced classification problem. Here the number of data points belonging to the minority class (“Disease”) is far smaller than the number of data points belonging to the majority class ("No Disease").

 Approaches to handle imbalanced classes

1.Undersampling
2.Oversampling
3.Creating synthetic data
4.Cost sensitive learning
5.Ensemble methods

First 3 methods has been implemented.

Conclusion:
In this jupyter notebook, I have implemented  random undersampling,over-sampling and SMOTE.

Some combination of these approaches will help us to create a better classifier. Simple sampling techniques may handle slight imbalance whereas more advanced methods like ensemble methods are required for extreme imbalances. The most effective technique will vary according to the dataset.

So, based on the above discussion, we can conclude that there is no one solution to deal with the imbalanced classes problem. We should try out multiple methods to select the best-suited sampling techniques for the dataset in hand. The most effective technique will vary according to the characteristics of the dataset.
