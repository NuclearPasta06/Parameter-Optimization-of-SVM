# Parameter-Optimization-of-SVM

## About SVM and Parameter Optimization 
Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

We can perform this task using GridSearchCV for optimizing these parameters.
In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset Information
The dataset for the project has been downloaded from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/Wine+Quality

The datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: The reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

Number of Instances: 5031

Number of Attributes: 12

## Final Result Table
![Screenshot 2023-04-20 014344](https://user-images.githubusercontent.com/83859149/233189426-db003caa-94fc-4c9b-b08f-00b2430788be.png)

## Convergence Graph
![download](https://user-images.githubusercontent.com/83859149/233192161-aefe38ce-daba-4f10-8186-957e09001821.png)

## Result
The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.61 having kernel = rbf, Nu = 0.98 and Epsilon = 7.88.

## Citation :
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.
Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009

## Submitted By:
Name : Saksham Yadav <br />
Roll No. : 102003673 <br />
Sub-Group: 3CO27
