# 🏥 Heart Disease Risk Prediction using Machine Learning

## 📌 Project Overview  
This project predicts heart disease risk levels in patients using machine learning models. The goal is to assist in early detection and classification of heart disease risk into categories:  

✅ No Heart Disease  
⚠️ Mild Risk  
⚠️ Moderate Risk  
❗ High Risk  
🚨 Severe Risk  

By leveraging data-driven insights, this model aims to support healthcare professionals and individuals in identifying potential risks early.  

---

## 📊 Dataset Details  

📌 **Source:** [Heart Disease Dataset – Kaggle](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data/code?datasetId=888463&sortBy=voteCount)  

**🔢 Features in the Dataset:**  
- **Demographics:** Age, Sex  
- **Health Indicators:** Chest Pain Type (cp), Resting Blood Pressure (trestbps), Serum Cholesterol (chol), Fasting Blood Sugar (fbs)  
- **ECG & Exercise Data:** Resting ECG (restecg), Max Heart Rate (thalch), Exercise-Induced Angina (exang), ST Depression (oldpeak)  
- **Additional Features:** Slope of Peak Exercise ST Segment (slope), Number of Major Vessels (ca), Thalassemia (thal)  

---

## 🚀 Models Used & Performance  

| Model                         | Accuracy   |
|--------------------------------|------------|
| Logistic Regression            | 54.50%     |
| K-Nearest Neighbors (KNN)      | 72.02%     |
| Support Vector Machine (SVM)   | 69.10%     |
| Decision Tree                  | 68.37%     |
| **Random Forest**              | 81.27%     |
| Gradient Boosting              | 70.56%     |
| **XGBoost (Best Model)**       | 82.00%     |
| AdaBoost                       | 50.85%     |
| Gaussian Naive Bayes           | 45.99%     |

### 🔥 **Best Model: XGBoost**  
✅ **Accuracy:** 82.00%  
📊 **Classification Report:**  
- **Precision:** 0.82 (Class 0)  
- **Recall:** 0.84 (Class 0)  
- **F1-Score:** 0.83 (Class 0)  
- **Overall Accuracy:** 0.82  

## 🔄 Future Improvements  
- Fine-tune hyperparameters of the **XGBoost** model for better performance.  
- Explore additional **features and engineered variables** to improve accuracy.  
- Test on **more diverse datasets** to enhance model generalization.  
- Experiment with **ensemble methods** and **neural networks** for further performance improvements.  

