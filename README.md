# Ireland Census Analysis and Supervised Machine Learning Models

## Project Overview
This project analyses Irish population census data from the Central Statistics Office (CSO) to identify demographic trends across census years, counties/cities, gender, age groups, and marital status.

The project combines:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualisation
- Feature Engineering
- Supervised Machine Learning

## Objectives
- Analyse population changes across census years
- Explore demographic distributions
- Identify regional population patterns
- Apply machine learning models to predict gender categories

## Dataset
Source:
Central Statistics Office Ireland (CSO)

Files:
- irelandpopulation.csv
- newdata_df_dataset.csv

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Support Vector Classifier (SVC)
- K-Nearest Neighbours (KNN)

## Model Performance
| Model | Accuracy |
|---|---|
| KNN | 51.46% |
| SVC | 48.60% |
| Logistic Regression | 47.73% |
| Random Forest | 42.84% |

## Key Findings
- Ireland’s population increased across census years.
- Dublin and Cork showed the highest population concentration.
- KNN achieved the strongest predictive performance.
- Demographic variables provided moderate predictive capability for gender classification.

## Repository Structure
- `ireland_population_analysis_ml.ipynb` → Main notebook
- `irelandpopulation.csv` → Original dataset
- `newdata_df_dataset.csv` → Processed dataset

## Future Improvements
- Hyperparameter optimisation
- Cross-validation techniques
- Additional demographic variables
- Advanced machine learning models
- Feature importance analysis

## Author
Rosilene Da Silva
