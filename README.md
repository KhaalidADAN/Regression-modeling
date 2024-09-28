# User Churn Prediction Using Binomial Logistic Regression

## Project Overview
This project focuses on predicting user churn for the Waze app using binomial logistic regression. The analysis aims to identify patterns in user behavior that lead to app uninstallation or reduced usage. The dataset includes user activity data, and the findings will inform marketing and product development strategies.

## Business Understanding
The primary stakeholders for this project are the Waze data team and the marketing department, seeking to reduce monthly user churn. Churn refers to users who have uninstalled or stopped using the Waze app. The challenge lies in identifying the factors contributing to user churn to enhance retention strategies.

## Data Understanding
The analysis utilizes user activity data over a specified timeframe. Key features include:
- `activity_days`: The number of days a user was active.
- `km_per_driving_day`: The average kilometers driven per day.

Data limitations include a potential lack of features that correlate strongly with user churn, which may hinder model accuracy. Exploratory Data Analysis (EDA) visualizations reveal trends and patterns in user behavior that correlate with churn rates.

## Modeling and Evaluation
The model employed is a binomial logistic regression, which is effective for predicting binary outcomes (churned vs. retained users). Key evaluation metrics include:
- **Accuracy**: Overall correctness of the model.
- **Precision**: The proportion of true positive predictions out of all positive predictions (53%).
- **Recall**: The proportion of true positive predictions out of all actual positives (9%).

Despite mediocre precision, the model highlights the importance of further data collection to improve recall and enhance predictive power.

## Conclusion
The analysis reveals that `activity_days` significantly impacts user retention, while the `km_per_driving_day` has less influence. Recommendations include:
- Conducting further data collection to uncover additional features that influence user churn.
- Refining the user profile targeted by Waze to tailor marketing strategies effectively.

Future steps involve testing additional models and incorporating new features to enhance predictive accuracy and inform business decisions.
