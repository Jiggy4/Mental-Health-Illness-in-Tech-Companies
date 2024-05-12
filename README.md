# Project Architecture for Mental Health Prediction in Tech Companies
#### Winner of 6th Annual Analytics Competition at Clark University
#### Overview
This project focuses on predicting mental health illnesses in tech companies by analyzing a dataset of 1,259 employees. The goal is to identify factors influencing employees' decision to seek mental health treatment and to develop strategies that enhance their well-being and overall mental health.

#### Data Description
Dataset Size: 1,259 records of tech company employees
Features: 27 independent variables related to workplace conditions, personal history, and demographics
Target Variable: Employee openness to seeking treatment
Technology Stack
Programming Language: Python
Libraries and Frameworks: Scikit-learn for machine learning models, Pandas for data manipulation, Matplotlib and Seaborn for data visualization
Machine Learning Models Used:
Logistic Regression
K-Nearest Neighbors (KNN)
Random Forest
XGBoost
Model Performance
Best Performing Model: XGBoost with an accuracy of 85.9%, sensitivity of 91.5%, and F1-score of 0.85
Model Evaluation Metrics: Accuracy, Error Rate, Sensitivity, Specificity, F1-score
Features and Model Selection
Feature Selection: Identified using XGBoost for determining relative influence
Model Insights: Key predictors include work interference, family history, availability of care options, coworker support, gender, anonymity in seeking help, existing wellness programs, and observed consequences of seeking treatment
Repository Structure
/data: Contains the dataset used in the project
/notebooks: Jupyter notebooks for exploratory data analysis and model training
/scripts: Python scripts for data preprocessing and model implementation
/models: Saved models and configuration files
/docs: Project documentation and results presentation
Installation and Setup
Clone the repository
Install required Python packages: pip install -r requirements.txt
Run Jupyter notebooks within the /notebooks directory to replicate the analysis
Practical Applications
Targeted Interventions: Designing workplace wellness programs tailored to the identified predictors
Policy Development: Informing policies that support mental health and well-being in the tech industry
Future Work
Extend the study to a larger and more diverse dataset
Update the survey questionnaire to capture current trends and factors affecting mental health in the tech industry
Limitations
Limited sample size and outdated dataset
Presence of selection bias and potential underreporting due to stigma
By providing this architecture in your GitHub README, viewers can quickly understand the scope, structure, and impact of your project, while also being able to navigate and utilize your repository effectively.
## Data Source

•	Dataset: IBM Employee Attrition Dataset  
•	Features: 1470 records, 35 features

## Methodology
#### Data Wrangling and Pre-processing  
#### Cleaning:  
Handling missing data, setting correct data types, dropping irrelevant attributes.
#### Encoding: 
Transforming categorical data into binary codes.
	
#### Exploratory Data Analysis (EDA)
Tools: Power BI for visual insights into the data distribution and relationships.
	
#### Model Development
Algorithms: Logistic Regression, XGBoost, KNN, Decision Tree, Random Forest.

Selection: Decision Tree was selected based on its performance in F1-Score and sensitivity, indicating a better balance between precision and recall.

## Tools and Technologies
Python: Main programming language for data wrangling, preprocessing, and model development.

Power BI: Used for creating interactive visualizations for EDA.

## Results & Discussion
The analysis identifies factors both increasing and decreasing the likelihood of attrition, such as distance from work, salary increases, and previous company experiences. These insights help in tailoring more effective employee retention strategies.

## Business Implication
Strategies like holistic compensation approaches, dynamic job evolution, and enhancing retention strategies through technology and culture enhancement are suggested.

## Limitations and Future Scope
Future versions can expand on the dataset to include more diverse roles and explore interdependence between variables using multivariate analysis. Updates to address pre-COVID data and improve inclusivity.


