# -Breast-Cancer-Classification---SVM
## 📌 Project Overview

This project uses **Support Vector Machine (SVM)** to classify breast cancer cases as **Benign** or **Malignant** based on medical features. The goal is to build an accurate and reliable machine learning model for early cancer detection.

---

## 📂 Dataset

* **File:** `Breast_Cancer.csv`
* **Target Variable:** Cancer diagnosis (Benign / Malignant)
* **Features:** Medical measurements related to tumor characteristics

---

## 🛠️ Technologies Used

* Python
* pandas, numpy
* scikit-learn
* matplotlib

---

## 🔄 Workflow

1. Load and inspect the dataset
2. Handle missing values and encode target labels
3. Split data into training and testing sets
4. Apply **StandardScaler** for feature normalization
5. Train SVM with **Linear** and **RBF** kernels
6. Tune hyperparameters using **GridSearchCV**
7. Evaluate model using accuracy, confusion matrix, and classification report
8. Plot **ROC curve** and calculate **AUC score**
9. Save the trained model for reuse

---

## ✅ Results

* RBF kernel performed better than linear SVM
* High accuracy and strong ROC–AUC score
* Model successfully distinguishes malignant and benign cases

---

## 🎓 Conclusion

Support Vector Machine is effective for breast cancer classification and can assist in early diagnosis when combined with proper feature scaling and hyperparameter tuning.

---

