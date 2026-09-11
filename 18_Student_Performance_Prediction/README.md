# Student Performance Prediction

Predicting whether a student will pass or fail their final exam based on study habits and background, using machine learning.

## Dataset

A synthetic dataset of 500 students with the following features:

- Study hours per day
- Attendance percentage
- Previous exam score
- Sleep hours
- Extracurricular participation
- Internet access

Students scoring 50 or above in the final exam are labelled as **Pass**, the rest as **Fail**.

## Project Steps

1. Data creation, inspection and summary statistics
2. Visualising score distributions and feature relationships
3. Correlation analysis
4. Encoding categorical features and creating the target
5. Train-test split and feature scaling
6. Logistic Regression and Random Forest models
7. Model evaluation and comparison
8. Feature importance analysis
9. Predicting results for new students

## Results

| Model | Test Accuracy |
|-------|---------------|
| Logistic Regression | 84% |
| Random Forest | 82% |

Study hours, previous exam score and attendance were the most important factors in predicting student performance.

## Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
