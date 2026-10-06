# Healthcare Patient Analytics

## Project Overview

Healthcare Patient Analytics is a data analysis project built using Python and Pandas to explore patient records, hospital information, medical conditions, billing amounts, admissions, insurance providers, and length of hospital stay.

The project focuses on data cleaning, exploratory data analysis (EDA), statistical analysis, data visualization, and extracting meaningful business insights from healthcare data.

> **Note:** The dataset used in this project is a synthetic healthcare dataset and should not be used for real-world clinical decision-making.

---

## Objectives

- Analyze patient demographics and medical conditions
- Understand patient distribution across hospitals and insurance providers
- Analyze billing amounts across different categories
- Calculate patient length of stay
- Identify relationships between age, length of stay, and billing
- Analyze admission trends over time
- Identify potential billing outliers
- Generate meaningful insights through data visualization

---

## Dataset

The dataset contains approximately 55,500 patient records and includes information such as:

- Patient Name
- Age
- Gender
- Blood Type
- Medical Condition
- Date of Admission
- Doctor
- Hospital
- Insurance Provider
- Billing Amount
- Room Number
- Admission Type
- Discharge Date
- Medication
- Test Results

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code
- Git & GitHub

---

## Project Structure

```text
Healthcare_Patient_Analystics/
│
├── Data/
│   ├── raw/
│   │   └── healthcare_dataset.csv
│   │
│   └── cleaned/
│       └── healthcare_cleaned.csv
│
├── Notebooks/
│   └── healthcare_eda.ipynb
│
├── Visualizations/
│   ├── patient_distribution_gender.png
│   ├── medical_condition_distribution.png
│   ├── age_group_distribution.png
│   ├── billing_by_medical_condition.png
│   ├── top_10_hospitals.png
│   ├── insurance_provider_distribution.png
│   ├── length_of_stay_vs_billing.png
│   ├── age_vs_billing.png
│   ├── billing_by_admission_type.png
│   ├── medical_condition_test_results.png
│   ├── admissions_by_year.png
│   ├── admissions_by_month.png
│   ├── billing_outliers.png
│   └── correlation_matrix.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Data Analysis Process

### 1. Data Loading

The healthcare dataset was loaded into a Pandas DataFrame for analysis.

### 2. Data Exploration

The dataset was explored using:

- `head()`
- `tail()`
- `shape`
- `columns`
- `dtypes`
- `info()`
- `describe()`
- `value_counts()`
- Unique value analysis

### 3. Data Quality Checking

The dataset was checked for:

- Missing values
- Duplicate records
- Data types
- Categorical values
- Date formatting

### 4. Feature Engineering

New analytical features were created, including:

- **Length of Stay**
- **Age Group**
- **Year**
- **Month**
- **Month Name**

Length of stay was calculated using admission and discharge dates.

### 5. Exploratory Data Analysis

The following analyses were performed:

- Patient distribution by gender
- Patient distribution by medical condition
- Patient distribution by age group
- Average billing by medical condition
- Top hospitals by patient count
- Patient distribution by insurance provider
- Length of stay vs billing amount
- Age vs billing amount
- Average billing by admission type
- Medical condition vs test results
- Admissions by year
- Admissions by month
- Billing amount outlier analysis
- Correlation analysis

---

## Key Visualizations

The project includes visualizations created using Matplotlib and Seaborn.

### Patient Distribution

The analysis examines patient distribution across gender and age groups.

### Medical Conditions

Patient records are compared across different medical conditions to understand the distribution of cases.

### Billing Analysis

Average billing amounts are compared across medical conditions and admission types.

### Hospital Analysis

The top hospitals are identified based on the number of patient records.

### Time Analysis

Admission patterns are analyzed by year and month to identify changes and variations over time.

### Relationship Analysis

Scatter plots are used to examine relationships between:

- Age and Billing Amount
- Length of Stay and Billing Amount

### Outlier Analysis

A boxplot is used to identify potential unusual billing values.

### Correlation Analysis

A correlation matrix is used to examine relationships among numerical variables such as age, billing amount, and length of stay.

---

## Key Insights

The analysis helps identify:

- Distribution of patients across demographic groups
- Common medical conditions
- Differences in average billing across medical conditions
- Hospitals with higher patient record volumes
- Distribution of patients across insurance providers
- Differences in billing across admission types
- Patterns between length of stay and billing
- Monthly and yearly admission patterns
- Potential billing outliers
- Relationships between numerical variables

The detailed findings and numerical results are available in the Jupyter Notebook.

---

## Business Recommendations

Based on the analysis, healthcare organizations could:

- Monitor patient admission trends to support resource planning
- Analyze billing patterns across admission types and medical conditions
- Investigate unusually high billing records
- Monitor hospital patient volumes
- Use demographic analysis to understand patient distribution
- Analyze length of stay to support operational planning
- Use data-driven dashboards for continuous healthcare performance monitoring

These recommendations are analytical observations from the dataset and should not be interpreted as clinical recommendations.

---

## Conclusion

This project demonstrates an end-to-end exploratory data analysis workflow using Python.

The project covers data loading, data quality checking, feature engineering, statistical analysis, exploratory data analysis, visualization, correlation analysis, and business insight generation.

It demonstrates practical skills in **Python, Pandas, NumPy, Matplotlib, Seaborn, data cleaning, EDA, and data visualization**, making it suitable as a Data Analyst portfolio project.

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the project folder

```bash
cd Healthcare_Patient_Analystics
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Notebooks/healthcare_eda.ipynb
```

Run the notebook cells from top to bottom.

---

## Skills Demonstrated

**Programming:**  
Python

**Data Analysis:**  
Pandas, NumPy

**Data Visualization:**  
Matplotlib, Seaborn

**Data Analytics:**  
Data Cleaning, EDA, Feature Engineering, Statistical Analysis, Correlation Analysis, Outlier Analysis

**Tools:**  
Jupyter Notebook, VS Code, Git, GitHub

---

## Author

**Aswin Biju**

Aspiring Data Analyst

GitHub: https://github.com/aswinbiju-analytics

LinkedIn: https://www.linkedin.com/in/aswinbiju012