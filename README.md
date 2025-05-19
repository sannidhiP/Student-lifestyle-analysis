📊 Student Lifestyle and Academic Performance
🔍 Project Overview
This project explores how lifestyle habits — such as sleep, stress, physical activity, socializing, and study hours — impact academic performance (CGPA) among students. Using R, I conducted exploratory data analysis, feature engineering, and machine learning modeling to uncover patterns that could inform student success strategies.

🧠 Key Questions Explored
Is there a point where increasing study hours no longer boosts GPA?
Does more socializing hurt academic performance?
What’s the relationship between stress levels and grades?
Can we profile student behavior into lifestyle clusters?
Which factors most accurately predict academic success?

📈 Dataset
Source: Simulated student lifestyle dataset

Features:
Study Hours, Sleep Hours, Stress Level
Social Hours, Physical Activity
GPA (Grades)

🔧 Methods Used
Data Cleaning & Wrangling (dplyr)
Visualization (ggplot2)

Feature Engineering:
Stress-sleep combinations
Lifestyle behavior categories
Study-sleep ratio
Clustering (k-means)
Predictive Modeling:
Linear Regression
Decision Tree
Random Forest

💡 Notable Insights
CGPA increases with study hours but flattens after ~8 hours/day — suggesting diminishing returns.
Moderate socializing (up to ~4 hours/day) doesn't harm grades, but excessive socializing may.
Students with moderate stress performed better than those with either low or high stress.
Surprisingly, students labeled “Not Balanced” (i.e., less healthy lifestyle) scored higher GPAs — suggesting that academic rigor may come at the cost of well-being.
Clustering revealed three profiles: Underperforming, Balanced, and High Performing with Healthy Habits.

🏆 Model Performance (Test Set)
Model	RMSE	MAE
Linear Model	0.505	0.404
Decision Tree	0.513	0.410
Random Forest	0.516	0.412

✅ The linear model performed best, offering a strong and interpretable relationship between lifestyle habits and GPA.
