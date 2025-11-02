# IBM_Analytics_Project

Project: Student Performance Analysis

Project Overview
This project analyzes the "Student Performance" dataset to understand the key factors that influence a student's Performance Index. The analysis involves:
Data Loading and Cleaning: Using pandas to load and inspect the dataset.
Exploratory Data Analysis (EDA): Using matplotlib and seaborn to create visualizations (histograms, scatter plots, box plots, and a correlation heatmap) to identify patterns.
Predictive Modeling: Building a Linear Regression model with scikit-learn to predict the Performance Index based on the available features.

Raw Dataset
The dataset used for this analysis is publicly available on Kaggle:
Link: https://www.kaggle.com/datasets/khansaafreen/student-performance

Insights & Findings
The analysis of 10,000 student records revealed several key insights:

Finding 1: Previous Scores are the Dominant Predictor
Previous Scores has the strongest relationship with Performance Index (a correlation of $0.91$). A student's past performance is the single best predictor of their future results.

Finding 2: Study Hours Have a Moderate Impact
Hours Studied shows a clear, moderate positive correlation ($0.37$). This is the most significant controllable factor for a student.

Finding 3: Some Factors Show No Significant Impact
Factors like Extracurricular Activities, Sleep Hours, and Sample Question Papers Practiced had correlations very close to zero, suggesting they have a negligible impact on performance in this dataset.

Finding 4: Performance is Highly Predictable
The Linear Regression model achieved an R-squared (R²) score of $0.99$. This means the features in this dataset can explain 99% of the variation in student scores, making performance highly predictable.

AI Support Explanation
This project was developed with the assistance of a Large Language Model (LLM). The AI's role was to act as a programming and analytics partner, not to run the analysis itself.

Conceptual Explanation: The AI provided clear explanations for statistical concepts (e.g., correlation, R-squared, Mean Squared Error) and the logic behind the code.

Insight Summarization: After the Python code was run and produced results (plots, model scores), the AI helped summarize those results into the clear, human-readable insights listed above.
