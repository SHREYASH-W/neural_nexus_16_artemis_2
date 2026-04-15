# Neural Nexus: Pediatric Genetic Disorder Classification

## Project Overview

**Neural Nexus** is a comprehensive machine learning project focused on exploratory data analysis (EDA) and preprocessing of heterogeneous pediatric medical data. The project aims to classify genetic disorders using structured clinical and demographic features extracted from real-world healthcare datasets.

The repository contains multiple analysis approaches, including exploratory data analysis both with and without preprocessing, enabling comparative study of how data preparation impacts feature understanding and model readiness.

## Dataset Description

The project utilizes a pediatric medical dataset containing heterogeneous clinical and demographic information with real-world challenges including missing values, noise, and class imbalance.

### Dataset Specifications:
- **Training Set**: 45 columns × 22,084 rows
- **Test Set**: 43 columns × 9,466 rows
- **File Format**: CSV
- **Files Included**: train.csv, test.csv, sample_submission.csv
- **Target Variables**: Genetic disorder classification and disorder subclass categorization
- **Data Characteristics**: Heterogeneous medical features, missing values, noise, class imbalance

## Repository Structure

### Notebooks:

1. **neural-nexus-eda-without-preprocessing.ipynb** - Initial exploratory analysis on raw data without preprocessing
2. **neural-nexus-eda-without-preprocessing-2.ipynb** - Alternative exploratory analysis without preprocessing
3. **neural-nexus-eda-with-preprocessing.ipynb** - Comprehensive EDA following data preprocessing

## Data Preprocessing Pipeline

The preprocessing workflow implemented addresses key data quality issues:

### Preprocessing Steps:

1. **Feature Selection**: Removal of non-significant columns that do not contribute to the problem statement
2. **Missing Value Imputation**: 
   - Mean-based imputation for age-related columns (Patient Age, Mother Age, Father Age)
   - Removal of remaining null/NaN values
3. **Categorical Encoding**: Label encoding applied to categorical features in the processed dataset
4. **Data Preparation**: Final cleaned dataset ready for modeling

## Exploratory Data Analysis (EDA)

The project employs a multi-staged EDA approach:

- **Unprocessed Data Analysis**: Two separate EDA notebooks examine raw data distributions, missing value patterns, and feature relationships without any preprocessing
- **Preprocessed Data Analysis**: One notebook presents EDA on cleaned, processed data with encoded features

This comparative approach enables:
- Understanding of raw data quality issues
- Impact assessment of preprocessing decisions
- Feature distribution insights post-cleaning
- Pattern identification in clinical variables
- Class imbalance analysis

<div align="center">

## Visualizations

<img src="https://github.com/user-attachments/assets/f55e8400-1e9f-4bf3-be13-9e74a0a2874e" width="80%" alt="Visualization 1" />

<br/>

<img src="https://github.com/user-attachments/assets/4fcc2a80-dfa2-4592-9eed-bbd4a5559dcd" width="80%" alt="Visualization 2" />

<br/>

<img src="https://github.com/user-attachments/assets/bb3348a6-4bfc-45ba-a674-c1a82ff62ae7" width="80%" alt="Visualization 3" />

<br/>

<img src="https://github.com/user-attachments/assets/50133fbd-faab-4830-8acc-4fe3fbfcef84" width="80%" alt="Visualization 4" />

<br/>

<img src="https://github.com/user-attachments/assets/dd1d1e20-e988-456a-b1ff-830c02535016" width="80%" alt="Visualization 5" />

<br/>

<img src="https://github.com/user-attachments/assets/87f78f66-babc-4afc-882a-05b995f7877e" width="80%" alt="Visualization 6" />

</div>



## Key Findings

- Identification of significant clinical and demographic predictors for genetic disorder classification
- Quantification of missing data patterns and their distribution across features
- Assessment of class imbalance in the target variable
- Feature relationship analysis in both raw and processed datasets

## Technologies & Libraries

- **Python 3.12.12**
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Jupyter Notebooks**: For interactive analysis and documentation

## Project Contributors

- Paras Rawal
- Priyanshu Bhatt
- Analysis and Preprocessing Team

## Dataset Access

The dataset contains:
- Clinical measurements and patient demographics
- Structured features for pediatric patients
- Multi-class disorder labels
- Train-test split prepared for model validation

## Use Cases

This preprocessed dataset and analysis framework can be applied to:
- Genetic disorder prediction and classification
- Medical diagnosis support systems
- Healthcare data quality assessment
- Machine learning model development in clinical contexts
- Feature engineering for medical ML applications

## Notes

- The dataset reflects real-world healthcare data challenges including missing values and imbalance
- Preprocessing decisions were made to balance data quality with information retention
- Both preprocessed and unprocessed analyses are available for comparison and validation
- Label encoding was applied to ensure compatibility with machine learning algorithms


