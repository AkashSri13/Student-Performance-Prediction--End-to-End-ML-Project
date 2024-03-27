### Problem statement
1. This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.

### Steps followed for this Machine Learning Project
1. Understanding the Problem Statement
2. Dataset
3. Data Checks to perform
4. EDA
5. Data Pre-Processing
6. Model Training
7. Selecting the best model

### Sequence of steps followed until Deployment
1. Github and Code Set Up
2. Project Structure, Logging And Exception Handling
3. Project Problem Statement, EDA And Model Training
4. Data Ingestion
5. Data Transformation using Pipelines
6. Model Training and Model Evaluating Component
7. Model Hyper Parameter Tuning
8. Created Prediction Pipeline using Flask Web App

### Dataset
1. Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
2. The data consists of 8 column and 1000 rows.

### Dataset information
1. gender : sex of students -> (Male/female)
2. race/ethnicity : ethnicity of students -> (Group A, B,C, D,E)
3. parental level of education : parents' final education ->(bachelor's degree, some college, master's degree, associate's degree, high school)
4. lunch : having lunch before test (standard or free/reduced)
5. test preparation course : complete or not complete before test
6. math score
7. reading score
8. writing score

### Data Checks Performed
1. Missing values
2. Duplicates
3. data type
4. the number of unique values of each column
5. statistics of data set
6. various categories present in the different categorical column

### Exploratory Data Analysis (EDA)
1. More Description can be found in the EDA and Modal Training files.

### Final Conclusions from EDA
1. Student's Performance is related with lunch, race, parental level education
2. Females lead in pass percentage and also are top-scorers
3. Student's Performance is not much related with test preparation course
4. Finishing preparation course is benefitial.

### Models used for Training
1. Linear Regression
2. Lasso
3. Ridge
4. K-Neighbours Regressor
5. Decision Tree
6. Random Forest Regressor
7. XGB Regressor
8. CatBoosting Regressor
9. AdaBoost Regressor
