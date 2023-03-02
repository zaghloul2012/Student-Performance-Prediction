
# Student Performance 

## Introduction
The idea of this project is to address the issue of high student failure rates in core classes such as Mathematics and Portuguese in the Portuguese education system. 

The goal is to develop more efficient student prediction tools that can aid the education domain in improving the quality of education and enhancing school resource management. 

## Dataset
This data approach student achievement in secondary education of two Portuguese schools. 

The data attributes include student grades, demographic, social and school related features) and it was collected by using school reports and questionnaires.

Data can be downloaded from [here](https://archive.ics.uci.edu/ml/datasets/Student+Performance)


## Model Development 
This project aims to develop and implement various regression models to predict the final score of a student (G3) based on the available features in the dataset.

The first step in this project was to clean, organize, and transform the data into a format that is acceptable by machine learning models. The data cleaning process involved removing missing values, removing outliers, and checking for data consistency. The transformed dataset was then used for model development.

Several regression models were developed and evaluated on the transformed dataset. The following are the models developed:

1. Simple Linear Regression: A simple linear regression model was developed, where the final score of the student (G3) was predicted based on the score of year 2 (G2). The relationship between G2 and G3 was found to be strong and statistically significant.

2. Multiple Linear Regression: A multiple linear regression model was developed using all the available features to develop a more complex but linear regression format.

3. Polynomial Regression: A polynomial regression model was developed by trying different models with different degrees to capture the non-linear relationship between the input features and the output variable.

4. Support Vector Regression: A support vector regression model was developed, which works by finding the optimal hyperplane that separates the data into two classes, with a maximum margin between the two classes.

5. Decision Tree Regression: A decision tree regression model was developed, which works by partitioning the data into smaller subsets based on the values of the input features and fitting a decision tree to predict the output variable.


## Results
A simple linear regression found to work well for our problem where the final score of the student (G3) was predicted based on the score of year 2 (G2). The relationship between G2 and G3 was found to be strong and statistically significant, leading to an R-squared value of about 80%.

![Simple Linear Regression Results](/simple_linear_regression_results.png "Simple Linear Regression Results")

Polynomial Regression: A polynomial regression model was developed by trying different models with different degrees to capture the non-linear relationship between the input features and the output variable. The polynomial regression model also showed good performance with an R-squared value of about 80%.

![Polynomial Linear Regression Results](/polynomial_linear_regression_results.png "Polynomial Linear Regression Results")



## Acknowledgements

 - [USING DATA MINING TO PREDICT SECONDARY SCHOOL STUDENT PERFORMANCE](http://www3.dsi.uminho.pt/pcortez/student.pdf)
 - [Student Performance Data Set](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Feedback

If you have any feedback, please reach out to us at youssef.zaghloul@ejust.edu.eg

