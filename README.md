# Heart Disease Prediction Model

Predicts heart disease using clinical features with a combined dataset of over 3,000 patients.

### Key Results
- **Accuracy**: 90%
- **Dataset**: 3,002 patients
- **Precision improvement**: +10% over baseline model
- **Model**: Random Forest with hyperparameter tuning and class balancing

### Datasets
- `heart.csv` → UCI Heart Disease dataset (303 records)
- `heart_failure_clinical_records_dataset.csv` → Additional clinical records (299 records, augmented)

### Tech Stack
- Python
- Scikit-learn
- Pandas
- Matplotlib & Seaborn

### How to Run
```bash
pip install pandas scikit-learn matplotlib seaborn
jupyter notebook Heart_disease_prediction.ipynb
