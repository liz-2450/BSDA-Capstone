# Predicting Online Course Completion Using Student Engagement Metrics

## Description
This project aims to identify which student engagement metrics are most associated with the completion of online courses.
By analyzing data from an online course platform, the goal is to help course developers improve completion rates through more effective content and personalized learning experiences.
This project uses machine learning models to predict course completion based on metrics such as time spent on courses, the number of quizzes taken, and average quiz scores.

## Data Description
The dataset includes engagement metrics from an online course platform, including:
* Time spent on the course
* Number of quizzes taken
* Average quiz scores
* Percentage of course content completed

Non-engagement variables include the course category and the type of device used to access the course.
The dataset was obtained from Kaggle [here](https://www.kaggle.com/datasets/rabieelkharoua/predict-online-course-engagement-dataset).

## Techniques and Tools
* **Languages and Libraries**: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
* **Machine Learning Models**: Supervised classification models, including Random Forest and Gradient Boosting
* **EDA and Visualization Tools**: Matplotlib and Seaborn for visualizing data distributions and correlations

## Analysis and Results
* Random Forest and Gradient Boosting models achieved accuracy scores above 95%.
* The most important engagement metrics were **Completion Rate** and **Quiz Scores**, which were identified as key predictors of course completion.

## Future Work
Future improvements could include:
* Expanding the dataset with more student engagement features (e.g., message board participation, frequency of logins to the course learning platform)
* Using clustering techniques to group students based on engagement patterns for more personalized insights.
