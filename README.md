Lab 02 – Breast Cancer Dataset Analysis

Overview

This experiment performs data analysis and preprocessing on the Breast Cancer Wisconsin dataset. The analysis includes dataset loading, data inspection, missing-value and duplicate checking, diagnosis encoding, feature and target separation, train-test splitting, correlation analysis, feature distribution visualization, and summary statistics.

Dataset

Dataset Name: breast_cancer_dataset.csv

The dataset contains breast cancer diagnostic information with numerical features related to cell nuclei characteristics.

Project Workflow

1. Load the Breast Cancer dataset
2. Explore the dataset
3. Check missing values
4. Check duplicate records
5. Encode the diagnosis column
6. Remove unnecessary columns
7. Separate features and target
8. Split the dataset into training and testing sets
9. Perform correlation analysis
10. Generate feature distribution visualizations
11. Calculate summary statistics

Data Preprocessing

The following preprocessing operations are performed:

- Check the structure of the dataset
- Check missing values
- Check duplicate records
- Convert diagnosis values into numerical form
- Remove the unnecessary ID column
- Separate input features and target variable
- Split data into training and testing sets

Visualizations

The experiment generates the following visualizations:

- Correlation Heatmap
- Feature Distribution Plots

Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

Project Structure

Lab-02/
│
├── 23mid0344_lab_02.ipynb
├── breast_cancer_dataset.csv
├── README.md
└── Figures/
    ├── correlation_heatmap.png
    └── feature_distribution.png

Installation

pip install numpy pandas matplotlib scikit-learn

How to Run

1. Clone or download the repository.
2. Place breast_cancer_dataset.csv in the same directory as the notebook.
3. Open 23mid0344_lab_02.ipynb using Jupyter Notebook or JupyterLab.
4. Install the required dependencies.
5. Run the notebook cells sequentially.
6. The analysis results and visualizations will be displayed.

Student Details

Name: Avinash A
Register Number: 23MID0344
Course: Advanced Predictive Analytics
Lab: Lab 02
