# SVM-Classification-Breast-Cancer

# Support Vector Machine (SVM) Classification

## 📌 Project Overview
This project implements Support Vector Machine (SVM) for binary classification using the Breast Cancer Dataset.

The project demonstrates:
- Linear SVM
- Non-linear SVM (RBF Kernel)
- Feature Scaling
- Hyperparameter Tuning
- Cross Validation
- Decision Boundary Visualization

---

## 📊 Dataset
Breast Cancer Wisconsin Dataset (available in Scikit-learn)

- Total Samples: 569
- Features: 30
- Classes:
  - Malignant (0)
  - Benign (1)

---

## 🛠 Technologies Used
- Python
- NumPy
- Matplotlib
- Scikit-learn

---

## ⚙️ Steps Performed
1. Data loading and preprocessing
2. Train-test split
3. Feature scaling using StandardScaler
4. Training SVM with Linear and RBF kernels
5. Hyperparameter tuning using GridSearchCV
6. Cross-validation evaluation
7. Decision boundary visualization using PCA

---

## 📈 Results
- Linear SVM Accuracy ≈ 97%
- RBF SVM Accuracy ≈ 98–99%

---

## 🚀 How to Run
```bash
pip install numpy matplotlib scikit-learn
python svm_project.py
