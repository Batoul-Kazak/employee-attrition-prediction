# Employee Attrition Prediction

## Overview
Predicts whether an employee will leave within 6 months using Logistic Regression as an interpretable baseline.

## Key Results
- **Accuracy:** 67%
- **ROC-AUC:** 0.74
- **Finding:** Random Forest achieved identical accuracy, confirming that current features lack strong predictive signal. Improvement requires richer data collection, not algorithmic complexity.

## Project Structure
- `notebook.ipynb` – Full reproducible implementation
- `report.pdf` – Short report covering problem, data, preprocessing, model, results, limitations, and conclusion

## Requirements
- Python 3.14.3
- pandas, numpy, scikit-learn, matplotlib, seaborn