# 🥗 Diet Recommendation Dataset

A synthetic diet recommendation dataset containing **1,000 records** for building and evaluating machine learning models that recommend personalized diet plans based on an individual's health and lifestyle characteristics.

## 📂 Dataset Information

- **File Name:** `diet_recommendation_dataset_1000.csv`
- **Number of Records:** 1,000
- **Number of Features:** 10
- **Format:** CSV

---

## 📋 Dataset Features

| Feature | Description |
|---------|-------------|
| Age | Age of the individual (years) |
| Gender | Gender (0 = Female, 1 = Male) |
| Height_cm | Height in centimeters |
| Weight_kg | Weight in kilograms |
| BMI | Body Mass Index |
| Activity_Level | Physical activity level (encoded) |
| Sugar_Level | Blood sugar level (mg/dL) |
| Cholesterol | Cholesterol level (mg/dL) |
| Goal | Health/Fitness goal (encoded) |
| Diet | Recommended diet plan (Target Variable) |

---

## 🎯 Target Variable

The **Diet** column contains the recommended diet category.

Example diet categories include:

- Low Carb
- Diabetic
- Heart Healthy
- *(Additional categories may exist depending on the dataset.)*

---

## 📊 Possible Machine Learning Tasks

This dataset can be used for:

- Diet Recommendation Systems
- Multi-class Classification
- Healthcare Analytics
- Nutrition Prediction
- Educational Machine Learning Projects

Popular algorithms include:

- Decision Tree
- Random Forest
- XGBoost
- LightGBM
- CatBoost
- Support Vector Machine (SVM)
- Logistic Regression
- Neural Networks

---

## 📁 Dataset Structure

```text
Age,Gender,Height_cm,Weight_kg,BMI,Activity_Level,Sugar_Level,Cholesterol,Goal,Diet
56,0,145,73,34.7,2,94,169,2,Low Carb
46,1,166,79,28.7,1,165,253,2,Diabetic
...
```

---

## 🚀 Example Usage

```python
import pandas as pd

# Load dataset
df = pd.read_csv("diet_recommendation_dataset_1000.csv")

# Display first five rows
print(df.head())
```

---

## 📈 Applications

- Personalized Nutrition Systems
- Healthcare AI
- Clinical Decision Support
- Fitness Recommendation Systems
- Educational Data Science Projects
- Classification Model Benchmarking

---

## ⚠️ Disclaimer

This dataset is intended for **educational, research, and machine learning practice purposes only**. It is not a substitute for professional medical or nutritional advice.

---

## 📜 License

This dataset is released under the **MIT License**. You are free to use, modify, and distribute it for educational and research purposes.

---

## 🤝 Contributions

Contributions are welcome!

If you find any issues or have suggestions for improving the dataset, feel free to open an issue or submit a pull request.

---

## ⭐ Support

If you find this dataset useful, consider giving the repository a ⭐ on GitHub.
