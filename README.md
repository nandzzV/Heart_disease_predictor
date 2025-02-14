# ❤️ Heart Disease Prediction with Machine Learning

This project uses **Machine Learning** to predict the risk of heart disease based on various health factors. It trains multiple models and provides a **user-friendly predictor**.

## 📌 Features
- **Data Visualization**: Analyze trends in heart disease data.
- **Multiple ML Models**: Compare Logistic Regression, Random Forest, SVM, KNN, and Gradient Boosting.
- **Heart Disease Predictor**: Input health data to get a prediction.
- **Formatted Model Comparison**: Uses a **pretty table** for model performance.
- **Jupyter Notebook Implementation**: Easy to run and modify.

## 🚀 Usage
1. Open **Jupyter Notebook**:
   ```sh
   jupyter notebook
   ```
2. Run `heart_disease_analysis.ipynb` to visualize data and predict data.

## 🏆 Model Performance
| Model                 | Accuracy | Precision | Recall | F1 Score |
|----------------------|----------|-----------|--------|----------|
| Logistic Regression | 85.2%    | 83.5%     | 86.1%  | 84.8%    |
| Random Forest       | 87.5%    | 85.8%     | 89.2%  | 87.4%    |
| SVM                 | 84.0%    | 82.7%     | 85.1%  | 83.9%    |
| KNN                 | 81.2%    | 80.5%     | 82.4%  | 81.4%    |
| Gradient Boosting   | 88.1%    | 86.7%     | 90.0%  | 88.3%    |

🏅 **Best Model:** Gradient Boosting (88.1% Accuracy)

## 🩺 Heart Disease Prediction Example
Modify `example_input` in the notebook:
```python
example_input = {
    'Age': 65, 'Sex_M': 1, 'Sex_F': 0, 'ChestPainType_ASY': 1,
    'RestingBP': 160, 'Cholesterol': 300, 'FastingBS': 1, 'MaxHR': 120,
    'ExerciseAngina_Y': 1, 'Oldpeak': 3.5, 'ST_Slope_Flat': 1
}
```
🔹 **Prediction:** 🚨 Heart Disease Detected!
