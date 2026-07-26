# ❤️ Heart Disease Prediction using Machine Learning

A Machine Learning project that predicts the likelihood of heart disease based on patient health parameters. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model deployment preparation.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals make informed decisions and provide timely treatment.

In this project, multiple Machine Learning classification algorithms are trained and compared to identify the most accurate model for predicting heart disease.

---

## 🎯 Objectives

- Predict whether a patient has heart disease.
- Perform data cleaning and preprocessing.
- Explore the dataset using visualization techniques.
- Compare multiple Machine Learning algorithms.
- Evaluate model performance using different metrics.
- Save the best-performing model for future predictions.

---

## 📂 Project Structure

```
Heart-Disease-Prediction/
│
├── data/
│   └── heart.csv
│
├── models/
│   └── heart_disease_model.pkl
│
├── notebook/
│   └── Heart_Disease_Prediction.ipynb
│
├── images/
│   ├── correlation_heatmap.png
│   ├── target_distribution.png
│   ├── confusion_matrix.png
│   └── feature_importance.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📊 Dataset Information

The dataset contains patient medical information used to predict heart disease.

### Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression (Oldpeak)
- Slope
- Number of Major Vessels
- Thalassemia

### Target

- **0** → No Heart Disease
- **1** → Heart Disease

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 🤖 Machine Learning Models

The following classification algorithms were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

---

## 📈 Workflow

1. Import Required Libraries
2. Load Dataset
3. Dataset Overview
4. Data Quality Check
5. Target Distribution
6. Exploratory Data Analysis (EDA)
7. Feature Selection
8. Train-Test Split
9. Feature Scaling
10. Model Training
11. Accuracy Comparison
12. Classification Report
13. Confusion Matrix
14. Feature Importance
15. Sample Prediction
16. Save Model

---

## 📊 Model Evaluation

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

The best-performing model was selected based on its overall evaluation metrics.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
```

Go to the project folder:

```bash
cd Heart-Disease-Prediction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

or

```bash
code .
```

Then open:

```
Heart_Disease_Prediction.ipynb
```

Run all notebook cells sequentially.

---

## 💾 Saving the Model

The trained model is saved using Joblib.

```python
import joblib

joblib.dump(model, "heart_disease_model.pkl")
```

Load the saved model:

```python
model = joblib.load("heart_disease_model.pkl")
```

---

## 📷 Sample Output

The notebook includes visualizations such as:

- Dataset Overview
- Target Distribution
- Correlation Heatmap
- Feature Importance
- Accuracy Comparison
- Confusion Matrix

---

## 📌 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Web Application using Flask
- Streamlit Dashboard
- Deployment on Render or Railway
- Real-time Prediction API

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 📜 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Developer

**Aman Kumar**

**B.Tech in Artificial Intelligence**

Python Developer | Machine Learning Enthusiast

---

⭐ **If you found this project helpful, please consider giving it a Star on GitHub!**
