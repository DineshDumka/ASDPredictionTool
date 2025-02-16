# Autism Prediction using Machine Learning

## 📌 Overview
This project aims to predict autism in individuals using machine learning techniques. The dataset is sourced from Kaggle, and various classification models have been implemented to achieve high accuracy in prediction.

## 📂 Dataset
- **Source**: [Kaggle Autism Diagnosis Competition](https://www.kaggle.com/competitions/autismdiagnosis/data)
- **Features**: Various personal and behavioral traits contributing to autism diagnosis.
- **Target Variable**: Whether an individual has autism (1) or not (0).

## ⚙️ Models Used
Several machine learning models were tested, and hyperparameter tuning was applied to achieve the best performance. The final model was evaluated using accuracy, precision, recall, and F1-score.

## 📊 Model Performance
- **Accuracy**: 81.88%
- **Confusion Matrix**:
  ```
  [[108  16]
   [ 13  23]]
  ```
- **Classification Report**:
  ```
                precision    recall  f1-score   support
  
            0       0.89      0.87      0.88       124
            1       0.59      0.64      0.61        36
  
     accuracy                           0.82       160
    macro avg       0.74      0.75      0.75       160
 weighted avg       0.82      0.82      0.82       160
  ```
- The model performs well for non-autistic cases but has room for improvement in predicting autistic cases.

## 🚀 How to Run the Project
### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/autism-prediction.git
cd autism-prediction
```

### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3. Run the Jupyter Notebook**
```bash
jupyter notebook
```
Open `Autism_Prediction_using_Machine_Learning.ipynb` and execute all cells.

## 🔥 Future Improvements
- **Handle class imbalance** using techniques like SMOTE or weighted loss functions.
- **Try deep learning models** (e.g., neural networks) for better feature extraction.
- **Feature engineering** to improve prediction accuracy.

## 📝 Conclusion
This project successfully implements machine learning techniques to predict autism with an accuracy of 81.88%. Further improvements can be made to enhance the model's performance, especially for underrepresented classes.
