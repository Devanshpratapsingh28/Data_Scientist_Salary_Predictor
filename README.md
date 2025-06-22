# Mobile_Price_Classification_Dataset

## Problem Statement :
In the rapidly evolving field of data science, understanding the trends and patterns in salaries is crucial for professionals and organizations alike. This dataset aims to shed light on the landscape of Data Science Salaries from 2020 to 2024. By analyzing salary data over this period, data enthusiasts, researchers, and industry professionals can gain valuable insights into salary trends, regional variations, and potential factors influencing compensation within the data science community.
In this problem we are predicting salary based on given features like role,work experience etc.

## Dataset Source : [Salary Dataset](https://www.kaggle.com/datasets/sazidthe1/data-science-salaries)

### Libraries Used 
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. Scikit Learn (Sklearn)

### Observations and Data Preprocessing Steps
1. Most of the companies are medium to large size.
2. Most of the company are situated in US and their employees are mostly US citizens.
3. Frequency wise highest job profiles are of Data Scientist,Data Engineer and Data Analyst.
4. Most of employees are Full Time employee.
5. Most of the employees are senior employees.
6. Salary of employee are seems to be normal distributed and hence it is very good.


### Models Tried 
1. Linear Regression and its varients like ElasticNet
2. Stochastic Gradient Descent(SGD) Regressor
3. SVM Regressor
4. DecisionTree Regressor
5. RandomForest 
6. Voting(ElasticNet, RandomForest ,DecisionTree, SGD)

### Accuracy Table

Below table is showing accuracy score of various models used in this task:

| Model            | R²   |
|------------------|------|
| Voting           | 0.59 |
| ElasticNet       | 0.58 |
| SGD Regressor    | 0.58 |
| Random Forest    | 0.56 |
| SVM Regressor    | 0.53 |
| Decision Tree    | 0.50 |


### Best Result : Voting(ElasticNet(3), RandomForest(2) ,DecisionTree(1), SGD(3))

