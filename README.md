# Problem Statement 
This data set consists of the marks secured by the students in Maths, Writing and Reading and background of the students from which they belong.
## Dataset

The dataset used is the StudentsPerformance.csv(https://www.kaggle.com/spscientist/students-performance-in-exams). 

The target variable is **Writing score**. **Writing Score** is scored by students in writing test. So, it can be predicting if **Reading score** is given.

**Target Variable: Writing Score**
<br>
**Mean Writing Score:** 68.054
<br>
**Max Writing Score:** 10
<br>
**Min Writing Score:** 100


## Model(s) Used

**Linear Regression**: Linear Regression is a machine learning algorithm based on supervised learning. It performs a regression task. Regression models a target prediction value based on independent variables. It is mostly used for finding out the relationship between variables and forecasting. Linear regression performs the task to predict **Writing score**  based on **Reading Score**. So, this regression technique finds out a linear relationship between **Reading Score** and **Writing Score**.

**Decision Tree**: Decision tree builds regression in the form of a tree structure. It breaks down a dataset into smaller and smaller subsets while at the same time an associated decision tree is incrementally developed. The final result is a tree with decision nodes (**Reading Score**) and leaf nodes (**Writing Score**).

## Future Work
I could have added other variable in account to predict writing score using Multiple regression.
