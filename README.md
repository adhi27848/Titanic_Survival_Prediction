# Titanic Survival Prediction Using Machine Learning

## Project Overview

This project uses the Kaggle Titanic dataset to develop machine learning models that predict whether passengers survived the Titanic disaster. It explores how passenger characteristics influence survival outcomes.

## Business and Research Problem

The primary research question is:

**Can machine learning models accurately predict Titanic passenger survival using demographic, socioeconomic, and travel-related information?**

## Dataset

The dataset comes from the Kaggle Titanic: Machine Learning from Disaster competition.

- Training dataset: 891 passengers
- Test dataset: 418 passengers
- Target variable: `Survived` (0 = Did Not Survive, 1 = Survived)

Features include passenger class, gender, age, fare, family relationships, and embarkation port.

Dataset source: https://www.kaggle.com/competitions/titanic

## Tools and Technologies

- Python and Jupyter Notebook
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Random Forest and Gradient Boosting

## Methodology

1. Load and inspect the training and test datasets.
2. Perform exploratory data analysis.
3. Identify and handle missing values.
4. Engineer features such as family size, passenger title, and cabin deck.
5. Train multiple classification models.
6. Evaluate performance using stratified cross-validation.
7. Generate predictions for Kaggle submission.

## Model Results

| Submission | Kaggle accuracy |
|---|---:|
| Version 1 — Baseline Random Forest | 76.076% |
| Version 2 — Improved Random Forest | 77.751% |

The second submission improved the leaderboard score by approximately 1.68 percentage points.

An additional model comparison achieved approximately 83.72% cross-validation accuracy using HistGradientBoosting, although this does not establish the corresponding Kaggle leaderboard performance.

## Key Learnings

This project helped me understand the complete machine learning workflow, including exploratory analysis, data preprocessing, feature engineering, model comparison, and prediction submission.

I also learned that strong cross-validation results do not guarantee identical performance on unseen competition data.

## Future Improvements

Future work will focus on improving feature engineering, tuning hyperparameters, testing ensemble methods, and reducing overfitting.

## How to Run

1. Download the Titanic competition datasets from Kaggle.
2. Place `train.csv` and `test.csv` in the notebook's expected data directory.
3. Install the required Python packages.
4. Open `Titanic_Survival_Prediction.ipynb`.
5. Run the notebook cells.
6. Generate `submission.csv` and upload it to Kaggle.

## Conclusion

This project demonstrates the practical application of supervised machine learning to a binary classification problem and highlights the importance of continuous model improvement.
