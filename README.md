# Student Depression Predictive Model

## Executive Summary

This data analytics project, completed in a team of 4, focuses on developing a machine learning model that predicts which students are at risk of experiencing depression.  

Using a student depression dataset sourced from kaggle.com, the team built and validated a **logistic regression model**.  This model was chosen because it's highly effective in scenarios where the outcome is binary.  In this case, a student being ***depressed or not depressed*** would be the possible outcomes.  

The final model was found to be ***approximately 84% accurate*** in predicting a student is at risk of depression.  

## Project Workflow

The analytics workflow of the project was documented in the accompanying Jupyter notebook.  The project consisted of the following activities:

- Developing business & analytical objectives
- Conducting exploratory data analysis (EDA)
- Cleansing & preprocessing data
- Constructing the machine learning model
- Model validation
- Deploying the model to make predictions

## Technology Stack

- **Programming Language:**  Python
- **Python Libraries:**  Numpy, Pandas, Matplotlib, Seaborn, Statsmodels, Sklearn 
- **Applications:**  Jupyter Notebook, MS Excel

## Instructions

1) Click on the following file within this repository:  `student_depression_project.ipynb`
2) Github will automatically render the jupyter notebook file
3) Review the python code, outputs, and data visualizations in the browser

## Project Report

For a comprehensive overview of the objectives, analysis, predictions, and recommendations, please refer to the full Data Analysis Report.

## Key Project Points

### Main Objective

Develop a predictive model to determine students at risk of depression by leveraging demographic, social, financial, and academic indicators

### Business Questions

- Who are the main stakeholders who will benefit most from our findings? 
- Which social, demographic, and academic variables should be considered for predicting students at risk of depression?
- Which groups of students can be identified as being at risk of depression?
- Which groups of students would benefit from additional mental health support?
- What intervention strategies can be developed, and which institutions or groups of people can implement these strategies?
- What strategies can be proposed to help students better manage their mental health?

### Analytical Questions

- Which columns of data are complete, consistent, and reasonable?
- Describe the distribution of depression amongst the student population? Is it a normal distribution?
- How strongly are the selected variables correlating with the depression score?
- How are the selected variables correlating with another?
- What is the best performing ML model for predicting students at risk of depression?
- Is the best performing ML model based solely on demographic factors? Social factors? Academic factors? Or a combination of different factors?
- What is the margin of error in these predictions?

### Summary Table of Variables

<img width="581" height="470" alt="image" src="https://github.com/user-attachments/assets/0a898b8f-2fa0-4bbe-8649-20bc28cd9404" />

### Conclusion

The logistic regression model for student depression performed exceptionally well, achieving an impressive 83.69% accuracy. This high accuracy makes it a strong tool for identifying at-risk students. When selecting features, we deliberately chose to set aside certain variables, like age and gender, as they showed weaker correlations with depression and didn’t align with the core psychological and social factors we wanted to emphasize. Instead, we focused on more meaningful variables that were highly correlated with depression, like academic pressure, financial stress, and work/study hours. The logistic regression model, also outperformed the alternative Random Forest model, highlighting its effectiveness as the preferred choice for this task. The team acknowledges the topic of student depression is heavily nuanced. The project data was pulled from one country and thus results can vary drastically given sociopolitical, cultural, and economic factors. As the topic speaks to many of us, it was extremely interesting to delve into, but the team also recognizes the limitations of the dataset in comparison to the depth and extensiveness of the topic and research of student depression. 

### Next Steps

Looking ahead, the team's recommendation for educational institutions is to use these insights to craft more targeted support programs, enhance early intervention strategies, and allocate mental health resources more effectively for students. This will ensure a comprehensive approach to supporting student well-being.
