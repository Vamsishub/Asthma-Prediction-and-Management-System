# Asthma-Prediction-and-Management-System

## Introduction
Asthma is a chronic respiratory disease affecting millions worldwide, yet current healthcare systems lack robust data models to predict and manage this condition effectively. The absence of comprehensive patient data and supportive resources hampers early detection and proactive treatment strategies, which are crucial for improving patient outcomes.

## Overview
This project leverages machine learning to enhance early detection and prediction capabilities for asthma. By integrating advanced technological solutions into healthcare, we aim to empower hospitals, doctors, and patients to anticipate asthma attacks, improving emergency preparedness and patient well-being. Our ultimate goal is to reduce emergency room visits and contribute to better long-term health outcomes, promoting personalized healthcare strategies for individuals at risk of or affected by asthma.

## Data Source
The project utilizes a comprehensive dataset from Kaggle, comprising over 639,590 patient records from the United States, collected between 2020 and 2022. This dataset includes various variables such as symptoms, age groups, and treatment outcomes, forming a rich resource for our analysis. The target variable for our predictive models is the presence of asthma, identified through health indicators and reported symptoms.

Dataset Link: Kaggle Asthma Disease Prediction Dataset

## Data Description
The primary dataset includes:

Symptoms: Detailed health indicators relevant to asthma.
Age Groups: Information categorized by age, enhancing the analysis across different demographics.
Severity and Treatment Outcomes: Insights into how severity levels affect treatment results, aiding predictive analysis.
Metadata: Presence of asthma, severity, and treatment outcomes are key variables that inform our predictive models.

## Descriptive Analysis: Tableau Visualization
Variable Importance and Decision Trees
Decision Tree Model: A foundational element in our descriptive analysis, offering an intuitive visualization of the data's structure in predicting asthma.
Key Variables: 'Race' and 'General Health' emerged as critical predictors, indicated by their prominence in the decision tree. The Youden index value of 0.2015 suggests moderate diagnostic ability.
Variable Importance Chart: 'Race' is the most significant predictor, followed by 'General Health' and 'Dry Cough'.

## Key Findings from Visualizations
Symptom Prevalence: Bar charts reveal that symptoms like sore throat and difficulty breathing vary across age categories, with older age groups exhibiting higher incidences. Notably, the "60-64" age group shows the highest incidence of both conditions.
Impact of Age, Breathing, and Sleep Time: Charts display how age relates to asthma symptoms, with increasing counts of breathing difficulties in older populations.
Demographic Insights: A treemap analysis shows a higher frequency of asthma among older White females (60-74 age range) compared to younger demographics.

## Model Evaluation
Random Forest Model: Identified 'Runny Nose' as the most influential variable for early asthma detection, with the model’s predictions aligning closely with observed data.
Logistic Regression Model: Focused on 'Pains' as a significant predictor, showcasing a Youden’s index of 0.2008, indicating moderate discriminative power. The confusion matrix reveals a need for improving model sensitivity.
Future Work

Data Collection Expansion: Broader data collection, including genetic and environmental variables, is recommended for enhanced predictive models.
Enhanced Data Quality and Monitoring: Improving data quality and implementing real-time monitoring systems could significantly improve asthma management and patient care.

## Lessons Learned and Conclusion
This analysis revealed a high degree of predictive accuracy, with symptoms such as 'Runny Nose' identified as key predictors in early asthma detection. While the Logistic Regression model provided valuable insights, it indicated the need for further refinement in model sensitivity.

The findings advocate for the expansion of data collection to encompass genetic and environmental factors, enhancing the precision of predictive models. By leveraging machine learning technologies, we aim to transform asthma diagnosis and management, moving closer to a healthcare system characterized by foresight, efficiency, and improved patient well-being.
