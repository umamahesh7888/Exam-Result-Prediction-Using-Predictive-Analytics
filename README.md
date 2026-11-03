# Exam-Result-Prediction-Using-Predictive-Analytics
## 1. Project Overview
Student Academic Performance Prediction is a Machine Learning project that predicts students' academic performance using student-related academic data.

The project uses different classification algorithms to predict student performance and compares their results to identify the best-performing model.

## 2. Objectives
- To analyze student academic performance.
- To identify the relationship between previous and final academic performance.
- To preprocess and encode categorical data.
- To build Machine Learning classification models.
- To evaluate and compare model performance.

## 3. Dataset
**Dataset Name:** Student Academics Performance

**Source:** UCI Machine Learning Repository

**Dataset ID:** 467

The dataset is fetched using the `ucimlrepo` Python library.

The target variable used in this project is:

- `atd` – Academic performance target variable.

## 4. Technologies and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- UCI ML Repository

## 5. Machine Learning Algorithms
The following classification algorithms are implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Support Vector Machine (SVM)

## 6. Project Workflow

1. Import required libraries.
2. Load the Student Academics Performance dataset.
3. Explore the dataset.
4. Separate features and target variable.
5. Check missing values and duplicate records.
6. Apply One-Hot Encoding.
7. Split the dataset into training and testing data.
8. Train classification models.
9. Predict student academic performance.
10. Evaluate and compare model performance.
11. Perform statistical analysis using the Chi-Square test.
12. Visualize the results.

## 7. Model Evaluation Metrics

The models are evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Log Loss
- Confusion Matrix

## 8. Model Performance Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.6296 | 0.6283 | 0.6296 | 0.6201 |
| Decision Tree | 0.3333 | 0.3148 | 0.3333 | 0.3221 |
| SVM | 0.5185 | 0.3878 | 0.5185 | 0.4392 |

### Best Performing Model

Based on the evaluation results, Logistic Regression achieved the highest performance among the three classification models, with an accuracy of **62.96%**.

## 9. Data Visualization and Statistical Analysis

The project includes:

- Distribution of student academic performance.
- Previous academic performance vs final performance.
- Confusion Matrix for Logistic Regression.
- Comparison of classification models.
- Chi-Square statistical test.

## 10. Installation

Install the required Python libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy ucimlrepo
```

## 11. How to Run the Project

1. Clone or download the repository.
2. Install the required libraries.
3. Open Jupyter Notebook.
4. Open `Student_Academic_Performance_Prediction.ipynb`.
5. Run all the cells sequentially.
6. Observe the model evaluation results and visualizations.

## 12. Conclusion

This project demonstrates how Machine Learning classification algorithms can be used to predict student academic performance.

Three classification algorithms were implemented and evaluated. Logistic Regression achieved the highest accuracy of 62.96%, followed by SVM and Decision Tree.

The project also explores the relationship between previous academic performance and final academic performance using visualization and statistical analysis.

## 13. Author

**Project Name:** Student Academic Performance Prediction

**Domain:** Machine Learning

**Language:** Python
