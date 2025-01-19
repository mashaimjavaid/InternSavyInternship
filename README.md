# Data Science Internship Tasks

This repository contains Jupyter Notebooks demonstrating work completed during a Data Science Internship. The tasks involve key data science processes such as data preprocessing, exploratory data analysis (EDA), visualization, and modeling. Each notebook represents a distinct task.

---

## Task 1: Predicting Admission Chances

### Notebook: `Task1_DataScience_Internship.ipynb`

#### Dataset: `Admission_Predict.csv`

#### Key Sections

1. **Data Exploration and Cleaning**
   - Columns: GRE Score, TOEFL Score, University Rating, CGPA, Research, and Chance of Admit.
   - Dataset characteristics: 500 rows, no null values, no duplicates.
   - Descriptive statistics and data types.

2. **Exploratory Data Analysis (EDA)**
   - Correlation Matrix.
   - Distribution Plots for `GRE Score`, `University Rating`, `Research`.
   - Scatter plots for key relationships (e.g., `CGPA` vs `Chance of Admit`).

3. **Feature Engineering and Splitting Data**
   - Independent variables (X) and target (`Chance of Admit`).
   - Data split into train-test (80-20 ratio).

4. **Standardization**
   - StandardScaler applied for consistent scaling.

5. **Model Training and Evaluation**
   - Models used:
     - Random Forest Regressor (best performance).
     - Linear Regression.
     - Decision Tree Regressor.
     - K-Nearest Neighbors.
   - Metrics: R-squared, Mean Absolute Error, Mean Squared Error.

6. **Conclusion**
   - Random Forest and Linear Regression exhibited the lowest Mean Squared Errors.

#### Technologies Used

- **Programming Language:** Python
- **Libraries:** pandas, matplotlib, seaborn, scikit-learn

---

## Task 2: Mall Customer Segmentation

### Notebook: `Task2_DataScience_Internship.ipynb`

#### Dataset: `Mall_Customers.csv`

#### Key Sections

1. **Data Exploration and Cleaning**
   - Renamed columns (e.g., `Genre` to `Gender`).
   - Dropped unnecessary columns (e.g., `CustomerID`).
   - Checked for duplicates and null values.

2. **Exploratory Data Analysis (EDA)**
   - Correlation Matrix.
   - Visualizations:
     - Gender distribution bar plots.
     - Boxplots of Age and Gender.
     - Age distribution by bins.

3. **K-Means Clustering**
   - Elbow method to determine optimal clusters.
   - Applied K-Means on `Age` and `Spending Score` features.
   - Visualized clusters and centroids.

4. **Encoding and Feature Selection**
   - Encoded `Gender` column for clustering.
   - Selected key features (`Age`, `Spending Score (1-100)`) for analysis.

5. **Conclusion**
   - Two distinct clusters identified based on Age and Spending Score.

#### Technologies Used

- **Programming Language:** Python
- **Libraries:** pandas, matplotlib, seaborn, scikit-learn

---

## How to Use

1. Clone this repository to your local machine:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the directory and open the desired notebook:

   ```bash
   jupyter notebook <notebook-name>.ipynb
   ```

3. Execute the cells sequentially to replicate the results.

---

## Prerequisites

Ensure you have the following installed on your system:

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Required libraries (install via `pip`):
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```

---

## Results

Each notebook provides:

- Comprehensive exploratory and advanced visual insights into datasets.
- Processed and cleaned data ready for analysis or modeling.
- Trained models with performance evaluation metrics.
- Actionable insights and recommendations.

---

## Contributing

If you wish to contribute to this project:

- Fork the repository.
- Create a new branch for your changes.
- Submit a pull request with a clear description of the modifications.

---

## Acknowledgments

- Internship mentors and collaborators.
- Open-source contributors for Python libraries used.
