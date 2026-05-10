# Ireland Census Analysis and Machine Learning

## Project Overview

This project analyses Irish population census data obtained from the Central Statistics Office (CSO) Ireland to explore demographic trends across census years, regions, age groups, gender, and marital status categories.

The primary focus of the project is exploratory data analysis (EDA), statistical analysis, and demographic visualisation. Supervised machine learning models were also applied experimentally to evaluate whether selected demographic variables could predict gender categories within the dataset.

Although the machine learning models achieved limited predictive performance, the project demonstrates a complete end-to-end data analysis workflow, including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualisation
- Feature Engineering
- Supervised Machine Learning
- Model Evaluation
- Hyperparameter Tuning
- Cross-Validation

---

## Project Objectives

- Analyse population changes across the 2011, 2016, and 2022 census years
- Explore demographic distributions across age groups, gender, and marital status
- Identify regional population patterns across Irish counties and cities
- Visualise demographic trends using statistical graphics
- Experiment with supervised machine learning classification models

---

## Dataset

**Source:**  
Central Statistics Office (CSO) Ireland

### Files
- `irelandpopulation.csv` → Original census dataset
- `newdata_df_dataset.csv` → Processed dataset

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Category Encoders

---

## Supervised Machine Learning Models

The following classification algorithms were evaluated:

- Logistic Regression
- Random Forest Classifier
- Support Vector Classifier (SVC)
- K-Nearest Neighbours (KNN)

---

## Model Performance

| Model | Accuracy |
|---|---|
| K-Nearest Neighbours (KNN) | 51.46% |
| Support Vector Classifier (SVC) | 48.60% |
| Logistic Regression | 47.73% |
| Random Forest Classifier | 42.84% |

---

## Key Findings

- Ireland’s population increased steadily across the 2011, 2016, and 2022 census years.
- Dublin and Cork demonstrated the highest population concentrations.
- Younger age groups represented a larger proportion of the population distribution.
- The K-Nearest Neighbours (KNN) model achieved the strongest predictive performance among the evaluated machine learning models.
- Overall machine learning performance remained moderate, indicating limited predictive separability within the available demographic variables.

---

## Limitations

The machine learning component demonstrated limited predictive performance because the dataset consists of aggregated demographic census information with relatively low separability between target classes.

As a result, the primary value of this project lies in demographic exploration, data visualisation, and the development of analytical workflows rather than in highly accurate predictive modelling.

---

## Repository Structure

```text
├── .gitignore  
├── README.md   
├── ireland_population_analysis_ml.ipynb
├── irelandpopulation.csv
├── newdata_df_dataset.csv
├── requirements.txt

## Future Improvements

Potential future enhancements include:

Additional feature engineering techniques
Inclusion of socioeconomic and geographic variables
Advanced machine learning algorithms
Feature importance analysis
Improved model interpretability
Expanded cross-validation strategies
Interactive dashboard visualisations

## Author
Rosilene Da Silva
