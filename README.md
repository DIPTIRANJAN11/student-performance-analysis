Student Performance Analysis Using Python and Machine Learning

Project Overview

This project analyses student academic performance using Python and Machine Learning. It explores student characteristics, study habits and academic grades to understand factors associated with academic performance.

Dataset

- Source: UCI Student Performance Dataset
- Records: 395 students
- Features: Student demographics, study habits, family background and academic grades
- Target variable: G3 (final mathematics grade)

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

Project Workflow

1. Dataset loading
2. Data exploration and cleaning checks
3. Exploratory Data Analysis
4. Data visualization
5. Categorical data encoding
6. Training and testing split
7. Random Forest Regression
8. Model evaluation
9. Actual vs Predicted visualization
10. Model comparison

Model Results

Metric| Model 1| Model 2
MAE| 1.16| 3.15
MSE| 3.80| 15.49
R² Score| 0.81| 0.24

Model 1 includes previous grades (G1 and G2). Model 2 excludes them.

Key Findings

Previous academic grades provide substantial predictive information about final mathematics grades in this dataset.

Limitations

The results are based on a single train-test split. Cross-validation and further testing are needed to assess model stability and generalization.

How to Run

1. Download the Jupyter notebook.
2. Open it in Google Colab.
3. Run the cells sequentially.
4. Review the model evaluation and visualizations.

Author

Dipti Ranjan

Project Type

Beginner Data Science and Machine Learning Project.
