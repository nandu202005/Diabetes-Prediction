# 🩺 Diabetes Prediction Using SVM (Machine Learning)

This project predicts whether a person is diabetic or not using the **PIMA Indians Diabetes Dataset**.  
The entire pipeline includes data preprocessing, feature scaling, SVM model training, accuracy evaluation, and real-time prediction.

---

## 📌 Project Overview
This machine learning project follows these steps:

- Load and explore the dataset  
- Clean and preprocess the data  
- Split into training & testing sets  
- Apply feature scaling  
- Train a Support Vector Machine (SVM) model  
- Evaluate performance using accuracy score  
- Build a simple prediction system for new input data  

---

## 🧠 Machine Learning Model Used

### **Support Vector Machine (SVM)**
- Kernel: `linear`  
- Suitable for binary classification  
- Works well with medical datasets  
- Provides a clear margin of separation  

---

## 📊 Model Performance

| Metric | Score |
|--------|--------|
| **Training Accuracy** | **78.66%** |
| **Testing Accuracy**  | **77.27%** |

---

## 📁 Dataset
- **Name:** PIMA Indians Diabetes Dataset  
- **Rows:** 768  
- **Features:** 8 medical attributes (Glucose, BMI, Age, etc.)  
- **Target:** 0 = Non-diabetic, 1 = Diabetic  

---

## 🚀 How to Run This Project

### 1️⃣ Install required libraries
```bash
pip install numpy pandas scikit-learn
