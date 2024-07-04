# Sepsis Classification

## Description:
* The objective of this project is to develop a model that can predict whether the patients will develop Sepsis or not.
* The dataset provided contains various information regarding the bloodwork and other measurements of the patients in ICU.
* We will go through Exploratory Data Analysis (EDA), model selection, and finally model evaluation.
* We uses Logistic Regression, Cost-Sensitive Decision Tree, and Balanced Random Forest and compare the results to each other. Details are available in the [project report](Project%20Report.pdf).

## How to run the jupyter notebook file:
1. Install the following libraries to your python environment: sklearn, numpy, matplotlib, pandas, imblearn
2. Open the jupyter notebook file using jupyter or Visual Studio Code.

## How to output prediction:
At the last code section of the jupyter notebook, there is a function to output prediction into a csv. Replace the function parameters for input and output file. 
The code above prediction function should be executed first since we will use values from train set to fill in missing data for prediction set.

## References
[1] “Sklearn.linear_model.logisticregression,” scikit. [Online]. Available: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html. [Accessed: 07-Apr-2023].<br/>
[2] “Decision tree,” GeeksforGeeks, 28-Mar-2023. [Online]. Available: https://www.geeksforgeeks.org/decision-tree/. [Accessed: 07-Apr2023].<br/>
[3] “Balancedrandomforestclassifier#,” imbalanced-learn. [Online]. Available: https://imbalanced-learn.org/stable/references/generated/imblearn.ensemble.BalancedRandomForestClassifier.html. [Accessed: 09-Apr-2023].<br/>
[4] “Sklearn.ensemble.randomforestclassifier,” scikit. [Online]. Available: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html. [Accessed: 07-Apr-2023].<br/>
