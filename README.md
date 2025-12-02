# Adaptive-learning-at-universities
PROJECT OVERVIEW:
Large university cohorts and diverse student backgrounds often lead to uneven mastery in core STEM and AI courses. This project develops an AI powered adaptive learning system designed to personalize practice, adjust pacing and provide early warnings for at-risk students.
The goal is to improve academic performance, reduce time to mastery and support instructors with data-driven insights.

OBJECTIVES AND RESEARCH QUESTIONS:
The core challenge addressed by this Supervised Learning approach is predicting student outcome early enough for intervention. How can we deliver personalized practice based on each student’s proficiency level?
Can we design adaptive pacing that reacts to individual progress?
How effectively can AI provide early warnings for struggling students?
What impact do adaptive systems have on pass rates and retention?

DATA SOURCES AND PREPARATION:
Data Source: The project is built on the Open University Learning Analytics Dataset (OULAD), which includes: LMS logs (clickstream data for engagement). Quizzes, exams, and final results. Student demographic and course registration information.
Data Preparation and Feature Engineering:
Target Definition: A binary target variable, is_at_risk, was defined based on the final student result (Fail/Withdrawn = 1, Pass/Distinction = 0). 
Feature Engineering: Raw VLE logs and assessment data were aggregated to create key predictive features: 
total_clicks - The student's overall engagement level. 
avg_score - The average performance on completed assignments. 
Preprocessing: Data underwent Standard Scaling and One-Hot Encoding before model training.

AI/ML Implementation and Results:
Model Selection and Training Technique - Supervised Classification (for early warning prediction). 
Models Trained - Logistic Regression and Random Forest Classifier. 
Mitigation - Models were trained with class_weight='balanced' to handle potential class imbalance and ensure accurate prediction of the at-risk class.

EXPECTED OUTCOMES:
Increased pass rates and student retention
Reduced time to mastery
Improved instructor analytics and early interventions
More equitable learning outcomes across diverse cohorts

SKILLS:
Machine Learning Supervised learning 

PRIVACY CONSIDERATIONS:
Student data protection (GDPR-compliant)
Transparency in AI explanations
Academic integrity safeguards
Opt-out options for students
Bias detection and monitoring
