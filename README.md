# Feature-Selection
The objective of this task is to assess the impact of feature selection on training and test datasets. 

Feature selection is the process of reducing the number of input variables when developing a predictive model.
It is desirable to reduce the number of input variables to both reduce the computational cost of modeling and, in some cases,
to improve the performance of the model.

Two datasets used in this task are SPECT_train.csv and SPECT_test.csv.
The idea is to identify good feature subsets using the training dataset and test these subsets on the test data.

For this task, Gradient Boosting classifier from sklearn is used to fit a model. As a baseline, performance (accuracy) on the train and test data is reported using all features. The results on the training data are based on cross validation. The results on the test data are based on hold-out.

Further, using the below three alternative feature subset selection strategies evalutaion has been performed.
One based on using information gain as a filter.
Wrapper-based forward sequential search.
Wrapper-based backward elimination.

A summary of the results obtained are shown as a bar chart, also discussing the stability and consistency of the results coming from the three feature selection methods are reported. 

