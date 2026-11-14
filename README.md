# Diabetes Progression Prediction using Regression

- **Problem:** Predict how much a patient's diabetes progressed one year after baseline, from 10 clinical measurements.
- **Dataset:** Diabetes dataset from scikit-learn, 442 patients, 10 features (age, sex, BMI, blood pressure and six blood serum measurements).
- **Models:** Linear Regression and Random Forest Regressor (80/20 train-test split, random_state=42).
- **Result:** Linear Regression R² = 0.453 (MAE = [MAE]) and Random Forest R² = 0.443 (MAE = [MAE]). The simpler model performed slightly better, so a more complex model was not an advantage on this small dataset.
- **Key finding:** BMI (0.355), s5 (0.231) and blood pressure (0.088) were the most important features in the Random Forest. This fits known metabolic risk factors. Feature importance shows what the model relied on, not what causes progression.
- **Limitation:** An R² of about 0.45 means the measurements explain under half of the variation, so this model is not suitable for clinical use.
- **Tools:** Python, pandas, scikit-learn, Google Colab.
