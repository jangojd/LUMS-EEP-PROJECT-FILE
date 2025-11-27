# Equity Equation Project
## Bridging the Education Access Gap Through Data-Driven Insights

![Analysis Overview](https://github.com/jangojd/LUMS-EEP-PROJECT-FILE/blob/4459a4a1c64613b39cdbd2ab7ae82151c97073c1/PSLM_Analysis/Nankana_Analysis/Figures/NanKana_summary_plot.png)

---

## 📋 Project Overview

The **Equity Equation Project** is a comprehensive quantitative research initiative that leverages advanced Machine Learning techniques to analyze and understand education access disparities for students aged 5-15 years across Lahore Division, Pakistan. By integrating data from the **Pakistan Standard Living Measurement (PSLM)** and **Multiple Indicator Cluster Survey (MICS)**, this project identifies critical socio-economic factors influencing educational accessibility and provides evidence-based recommendations for policymakers.

---

## 🎯 Key Objectives

- **Data Integration**: Merge PSLM and MICS datasets separately using STATA for comprehensive analysis
- **Regional Analysis**: Conduct in-depth analysis of education accessibility patterns in Lahore Division
- **Factor Identification**: Discover and quantify socio-economic variables affecting education access
- **Predictive Modeling**: Develop robust Machine Learning models to determine the most significant indicators
- **Policy Insights**: Generate actionable recommendations to improve educational equity and reduce access disparities

---

## 📊 Data Sources

| Source | Description | Coverage |
|--------|-------------|----------|
| **PSLM** | Pakistan Standard Living Measurement Survey | Comprehensive household socio-economic data |
| **MICS** | Multiple Indicator Cluster Survey | Child-focused indicators and education metrics |
| **Geographic Focus** | Lahore Division | Primary analysis region |
| **Age Group** | 5-15 years | Target population for education access analysis |

---

## 🔬 Methodology

### 1. **Data Preprocessing**
- Comprehensive cleaning and validation of raw survey data
- Strategic handling of missing values using appropriate imputation techniques
- Standardization and normalization of variables for consistent analysis
- Creation of binary and categorical variables for modeling

### 2. **Exploratory Data Analysis (EDA)**
- Distribution analysis and statistical profiling
- Correlation and multicollinearity assessment
- Trend identification across demographic segments
- Visualization of key patterns and relationships

### 3. **Feature Engineering**
- Extraction of key socio-economic indicators (income, parental education, household size)
- Creation of composite indices (poverty scores, accessibility indices)
- Domain knowledge integration for meaningful variable transformations
- Dimensionality reduction techniques where applicable

### 4. **Machine Learning Models**
- **Classification Models**: Logistic Regression, Random Forest, Gradient Boosting, SVM
- **Regression Models**: Linear Regression, Ridge/Lasso, XGBoost
- **Ensemble Methods**: Voting classifiers and stacking approaches
- Cross-validation and hyperparameter tuning for optimal performance

### 5. **Model Evaluation & Interpretability**
- Comprehensive performance metrics (Accuracy, Precision, Recall, F1-Score, AUC-ROC)
- Feature importance analysis using SHAP values and permutation importance
- Identification of significant variables driving education access disparities
- Sensitivity analysis for robust insights

---

## 🛠️ Technologies & Tools

| Component | Tools |
|-----------|-------|
| **Data Wrangling** | Python (Pandas, NumPy) |
| **Statistical Analysis** | SciPy, StatsModels |
| **Machine Learning** | Scikit-Learn, XGBoost, LightGBM |
| **Data Visualization** | Matplotlib, Seaborn, Plotly |
| **Data Merging** | STATA, Python |
| **Notebooks** | Jupyter Notebooks |
| **Version Control** | GitHub |
| **Documentation** | Markdown, Jupyter |

---

## 📁 Repository Structure

```
📂 Equity-Equation-Project
 ├── 📁 data
 │   ├── raw/                    # Original PSLM and MICS datasets
 │   └── processed/              # Cleaned and merged datasets
 │
 ├── 📁 notebooks
 │   ├── 01_data_merging.ipynb   # STATA preprocessing and merging
 │   ├── 02_eda.ipynb            # Exploratory data analysis
 │   ├── 03_feature_engineering.ipynb
 │   └── 04_model_training.ipynb # ML model development
 │
 ├── 📁 models
 │   ├── trained_models/         # Serialized ML models
 │   └── evaluation_metrics.csv   # Performance evaluation results
 │
 ├── 📁 reports
 │   ├── analysis_summary.pdf    # Comprehensive findings report
 │   ├── visualizations/         # Key charts and graphs
 │   └── policy_recommendations.md
 │
 ├── 📁 assets
 │   └── analysis_overview.png   # Key visualization for README
 │
 ├── 📄 README.md                # Project documentation
 ├── 📄 requirements.txt         # Python dependencies
 ├── 📄 STATA_commands.do        # Data merging scripts
 └── 📄 LICENSE                  # MIT License

```

---

## 🚀 Quick Start Guide

### Prerequisites
- Python 3.8+
- STATA (for data merging)
- Git
- Jupyter Notebook

4. **Submit a pull request** with detailed description of changes and rationale

### Reporting Issues
Found a bug or have a suggestion? Please open an issue with:
- Clear description of the problem
- Steps to reproduce (if applicable)
- Expected vs. actual behavior
- Relevant system information

---
---

## 📧 Contact & Collaboration

For questions, collaborations, or further information about the Equity Equation Project:

| Role | Name | Email | GitHub |
|------|------|-------|--------|
| **Research Associate** | Jawad Ali | jawadaliv28@gmail.com | [@jangojd](https://github.com/jangojd) |
| **Research Associate** | Anees Amjad | - | - |
| **Principal Investigator (PI)** | Dr. Farah Nadeem | - | - |



