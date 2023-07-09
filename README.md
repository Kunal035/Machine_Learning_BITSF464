Repository made for the Assignments of the machine learning course.]

**Project Description**


**Assignment 1:**

The census-income dataset contains census information for 48,842 people. It has 14 attributes for each person (age, workclass, fnlwgt, education, education-num, marital-status, occupation, relationship, race, sex, capital-gain, capital-loss, hours-per-week, and native-country) and a Boolean attribute class classifying the input of the person as belonging to one of two categories >50K, <=50K. Given the attribute values, the prediction problem here is classifying whether a person’s salary is >50K or <= 50K. The data description, training data set and testing data set can be found in the folder Assignment 2.
Build a prediction model using the following classifiers to predict whether a person’s income is <50K or ≥ 50K
i. There are missing values for some of the attributes and data tuples. You should apply the appropriate techniques for handling missing values.

ii. There are some continuous attributes among the 14 features. You may have to discretize these attributes using the most appropriate techniques if required.

iii. Construct the optimal-sized decision tree for predicting whether the income of a given person is >50K or <= 50K using the census-income dataset from the US Census Bureau. The optimal-sized decision tree can be obtained by applying the “Reduced Error Pruning” technique you learned in class. A graph will depict the number of vertices vs errors for training, validation, and testing data. The validation data set should be taken to 50% of the testing dataset and the remaining 50% should be used as testing data.

iv. Combine training and testing data points. Randomly select 67% of the data points as training data set and the remaining data points as testing data set. Build a decision tree using the same procedure in (iii).

v. Compare the optimal decision tree in steps (iii) and step (iv). Comment whether the two decision trees are the same or not, and justify your observation.

vi. Interpretability: Write down the rules that could be derived from the decision tree. Comment whether these rules are intuitive or not.

vii. Construct a Random Forest classifier and compare its results with the results of the decision trees obtained in (iii) and (iv).

viii. Report: You should develop a consolidated report on the methodology and techniques for building decision trees. The detailed results, along with appropriate graphs and tables, should be included in the report. You should discuss the strengths and weaknesses of the systems that have been built.


**Assignment 2:**

Continuing with the same dataset, construct:

1) a) Naïve Bayes Classifier
   b) Logistic Regression
   c) Neural Network classifiers with 1, 2 and 3 hidden layers
2) Combine training and testing data points. Randomly select 67% of the data points as training dataset and the remaining data points as testing data set.
3) Put up a comparative study of the following algorithms and figure out the optimal classifier
    a. Naïve Bayes Classifier
    b. Logistic Regression
    c. Neural Network classifiers with 1, 2 and 3 hidden layers
    d. Decision Tree Classifier (optimal one you obtained in Assignment 1)
    e. Random Forest
