
# Parkinson's Disease Prediction Using Machine Learning

## Project Overview
This project explores the use of machine learning to analyse voice measurements and distinguish between healthy individuals and individuals with Parkinson's disease.

## Objectives
- Explore and understand the voice-measurement dataset.
- Perform exploratory data analysis and visualisation.
- Prepare features for machine learning.
- Train and compare three classification models.
- Evaluate model performance using multiple metrics.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load and inspect the dataset.
2. Check for missing values.
3. Explore feature distributions and correlations.
4. Split the data into training and testing sets.
5. Apply feature scaling.
6. Train Logistic Regression, Decision Tree, and Random Forest models.
7. Compare models using accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrices.

## Dataset
The dataset contains biomedical voice measurements and a status label:
- `0` — Healthy
- `1` — Parkinson's disease

Dataset source: https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set

## Results
The notebook contains the model evaluation metrics and visualisations used to compare the three classifiers. The best-performing model is determined from the evaluation results.

## Limitations and Future Improvements
- The dataset contains a relatively small number of voice recordings.
- Multiple recordings may belong to the same participant.
- Testing on recordings from completely new participants would provide a stronger evaluation.
- Additional data and features could be explored in future work.


