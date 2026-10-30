# EDA PROJECT
# Exploratory Data Analysis (EDA) – Mroz Dataset

**Author:** Pratyay Majhi  
**Register Number:** 23BDS0018  
**Project Type:** Exploratory Data Analysis  
**Platform:** Google Colab / Python

---

## 📌 Project Overview

This project focuses on performing comprehensive Exploratory Data Analysis (EDA) on the **Mroz Dataset** to identify meaningful patterns, distributions, correlations and relationships among demographic, educational, economic and employment-related variables.

The primary objective is to understand the factors associated with women's labour-force participation, wages, education, family income and working hours through statistical analysis and data visualization.

The project follows a structured analytical workflow, starting from raw data loading and preprocessing to statistical exploration and advanced analytical techniques.

## 🎯 Objectives

- Understand the structure and characteristics of the dataset.
- Identify and handle missing values.
- Detect and manage outliers.
- Perform data cleaning and feature engineering.
- Apply normalization and standardization techniques.
- Conduct univariate, bivariate and multivariate analysis.
- Examine correlations and statistical relationships.
- Explore patterns in women's employment and economic characteristics.
- Generate meaningful insights through visualizations.

## 📂 Dataset Information

The project uses the Mroz dataset, which contains information about women's demographic and economic characteristics.

| Attribute | Description |
|---|---|
| Total observations | 753 |
| Total features | 23 |
| Dataset type | Structured tabular data |
| Data source | Mroz dataset |
| Format | CSV |

### Important Features

- `age` – Age of the woman.
- `educ` – Years of education.
- `exper` – Work experience.
- `wage` – Wage information.
- `lwage` – Logarithm of wage.
- `hours` – Annual working hours.
- `faminc` – Family income.
- `kidslt6` – Number of children below six years.
- `kidsge6` – Number of children aged six or above.
- `city` – City-related indicator.
- `inlf` – Labour-force participation indicator.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Data preprocessing and scaling |
| SciPy | Statistical analysis |
| Google Colab | Development environment |

## 🔄 Project Workflow

### 1. Data Loading and Exploration

- Imported the required Python libraries.
- Loaded the Mroz dataset using Pandas.
- Examined the first and last observations.
- Checked dataset dimensions, column names and data types.
- Generated descriptive statistical summaries.

### 2. Basic Statistical Analysis

Calculated the following statistical measures:

- Mean
- Median
- Standard deviation
- Variance
- Minimum and maximum
- Skewness
- Kurtosis
- Unique values

These measures helped understand the distribution and variability of numerical features.

### 3. Missing Value Analysis

- Identified missing values in individual columns.
- Calculated missing-value percentages.
- Visualized missing values.
- Applied median imputation for numerical variables.
- Used mode-based imputation for categorical variables.
- Verified missing values after imputation.

### 4. Data Cleaning

- Checked and removed duplicate records where present.
- Standardized column names.
- Examined data types.
- Converted numerical binary indicators into meaningful categorical labels.

### 5. Outlier Detection and Handling

Used the **Interquartile Range (IQR)** method to identify extreme observations.

The IQR is calculated as:

`IQR = Q3 - Q1`

Outlier boundaries:

- Lower Bound = Q1 - 1.5 × IQR
- Upper Bound = Q3 + 1.5 × IQR

Applied capping to selected numerical features to reduce the influence of extreme observations while retaining the records.

### 6. Feature Engineering and Data Transformation

- Created total number of children.
- Grouped age into meaningful age categories.
- Grouped education into education levels.
- Applied logarithmic transformations to selected skewed variables.
- Applied Min-Max normalization.
- Applied StandardScaler for standardization.

### 7. Univariate Analysis

Analyzed individual variables using:

- Histograms
- Box plots
- Count plots
- Frequency distributions

Explored age, education, family income, labour-force participation and working hours.

### 8. Bivariate Analysis

Investigated relationships between pairs of variables using:

- Scatter plots
- Box plots
- Bar plots
- Regression plots

Examples:

- Experience vs Wage
- Education vs Average Wage
- Family Income vs Labour-Force Participation
- Age vs Annual Working Hours
- Number of Children vs Working Hours

### 9. Multivariate Analysis

Explored multiple variables simultaneously using:

- Correlation heatmaps
- Pair plots
- Multivariate scatter plots
- Group-wise comparisons

This helped identify relationships among demographic, educational and economic variables.

### 10. Statistical Analysis

Applied statistical techniques to investigate relationships and distributions.

The analysis includes descriptive statistics, correlation analysis and categorical association testing where implemented in the notebook.

## 📊 Key Observations

- The dataset contains 753 observations and 23 features.
- The wage and log-wage variables contain missing observations.
- Working hours exhibit a positively skewed distribution.
- Education and wage show a positive association.
- Family income varies across labour-force participation categories.
- Age, education, experience and family characteristics provide useful dimensions for understanding employment patterns.

## 📈 Visualizations

The project includes several visualizations to understand the dataset:

- Age distribution histogram.
- Family income box plot.
- Labour-force participation count plot.
- Education distribution.
- Experience versus wage scatter plot.
- Education versus average wage bar plot.
- Age versus working hours scatter plot.
- Correlation heatmap.
- Pair plot of selected numerical variables.
- Multivariate scatter plots.

## 💡 Conclusion

This project demonstrates a complete EDA workflow using Python and statistical visualization techniques.

Through data preprocessing, missing-value treatment, outlier handling, feature engineering and statistical exploration, the project provides a structured understanding of the Mroz dataset.

The analysis highlights the importance of education, work experience, family characteristics and demographic factors when exploring women's employment and economic patterns.

The project also demonstrates how data visualization and statistical methods can transform raw data into meaningful insights.

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/PRATYAYDEVIL/BOX-OFFICE.git
   ```

2. Navigate to the project directory:

   ```bash
   cd BOX-OFFICE
   ```

3. Install the required dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy
   ```

4. Open the Jupyter Notebook or upload it to Google Colab.

5. Execute the notebook cells sequentially.

## 📚 Learning Outcomes

- Practical understanding of Exploratory Data Analysis.
- Experience with real-world structured datasets.
- Understanding of missing-value imputation.
- Knowledge of statistical distributions and outlier detection.
- Practical application of data normalization and standardization.
- Ability to interpret univariate, bivariate and multivariate visualizations.
- Improved understanding of statistical relationships and data-driven insights.

---

**Developed by Pratyay Majhi | 23BDS0018**

*Exploring data, discovering patterns, and transforming information into insights.*

