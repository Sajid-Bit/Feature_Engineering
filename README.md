# Feature Engineering & Feature Selection


## Motivation
Feature Engineering & Selection is the most essential part of building a useable machine learning project, even though hundreds of cutting-edge machine
learning algorithms coming in these days like deep learning and transfer learning

## Feature Selection
Feature selection is the process of identifying and selecting a subset of features from the original data set to use as inputs in a machine learning algorithm.
<br/>
Data sets usually contain a large number of features. We can use multiple algorithms to quickly disregard irrelevant features and identify those important features in our data.
<br/>
Feature selection algorithms can be divided into 1 of 3 categories: <br/>
> Filter methods <br/>

> Wrapper methods <br/>

> Embedded methods <br/>


##### Filter methods comprise basic data preprocessing steps to remove constant and duplicated features and statistical tests to assert feature importance.
##### Wrapper methods wrap the search around the estimator. They use backward and forward selection to examine and identify the best set of features.
##### Embedded methods combine feature selection with the fitting of the classifier or regression model.

# Why do we select features?
Feature selection is key to creating easier to interpret and faster models, as well as to avoiding overfitting. When creating machine learning models to use in the real-world, feature selection is an integral part of the machine learning pipeline.

## Filter Methods:
* Chi-square test for categorical variables
* ANOVA for continuous variables and binary or multiclass target variables
* Pearson’s correlation for continuous variables in regression
* Information gain
* Mutual information

## Wrapper Methods:
* Forward selection of features
* Backward selection of variables
* Exhaustive search
## Embedded Methods:
* Lasso regularization
* Linear models coefficients
* Feature importance derived from decision trees and random forests

# Filter Methods
* Filter methods comprise basic data preprocessing steps to remove constant and duplicated features and statistical tests to assert feature importance.
* These methods rely only on the characteristics of these variables, so features are filtered out of the data before learning begins. 
* Univariate filter methods evaluate each feature individually. 
### Filter Methods: Advantages:
* They are computationally inexpensive, you can process thousands of features in a matter of seconds.
* Filter methods are very good for eliminating irrelevant, redundant, constant, duplicated, and correlated features.
### Filter Methode Techniques:
#### Chi-square test for categorical variables:
What is categorical variables: 
Categorical variables contain a finite number of categories or distinct groups. Categorical data might not have a logical order. For example, categorical predictors include gender, material type, and payment method.


