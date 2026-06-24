**AI-Based Hiring Prediction System**
End-to-End Machine Learning Project for Resume Screening

Project Overview

The AI-Based Hiring Prediction System is a Machine Learning project designed to automate the resume screening process used in recruitment and HR analytics. The system analyzes candidate information such as skills, work experience, education, certifications, projects, and salary expectations to predict whether a candidate is likely to be Hired or Rejected.

This project simulates a real-world AI-powered recruitment solution that helps organizations reduce manual effort, improve hiring efficiency, and make data-driven recruitment decisions.

**Objectives**

Analyze candidate resume data.
Perform data preprocessing and feature engineering.
Build and train a Machine Learning model.
Predict hiring decisions automatically.
Evaluate model performance using standard metrics.
Identify the most influential factors affecting hiring decisions.

**Dataset Description**
The dataset contains more than 1,000 synthetic candidate resumes with the following attributes:

**Feature**          	**Description**
Resume_ID	           Unique identifier
Name	               Candidate name
Skills	             Technical skills
Experience (Years)	 Total work experience
Education	           Highest qualification
Certifications	     Professional certifications
Job Role	           Applied job position
Salary Expectation ($)	Expected salary
Projects Count	     Number of completed projects
Recruiter Decision	 Hiring decision (Target Variable)

**Target Variable**
Hire → 1
Reject → 0

**Technologies Used**
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Google Colab

Machine Learning Workflow
**1. Data Collection**
Load the resume screening dataset.

**2. Data Exploration**
Display dataset information
Statistical summary
Check missing values

**3. Data Preprocessing**
Handle missing values
Encode categorical variables
Remove unnecessary columns

**4. Exploratory Data Analysis**
Hiring distribution visualization
Correlation analysis
Feature importance analysis

**5. Model Building**
Train a Random Forest Classifier to predict hiring decisions.

**6. Model Evaluation**
Evaluate performance using:

Accuracy Score
Confusion Matrix
Precision
Recall
F1-Score
