# 🩺 Disease Prediction System using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?style=flat-square&logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

A Machine Learning-based system that predicts possible diseases from user-input symptoms. It trains and compares multiple classification algorithms, automatically selects the best-performing model, and delivers accurate predictions — all in a user-friendly interface.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Technologies Used](#️-technologies-used)
- [ML Models](#-machine-learning-models)
- [Dataset](#-dataset)
- [How It Works](#️-how-it-works)
- [Output](#-output)
- [Getting Started](#-getting-started)
- [Limitations](#-limitations)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 📌 Overview

This project addresses the challenge of early disease identification by allowing users to enter their symptoms and receive an instant prediction. Rather than relying on a single model, the system trains several classifiers and selects the most accurate one — ensuring robust and reliable results.

---

## 🎯 Features

- ✅ Predicts diseases based on user-provided symptoms
- ✅ Trains and compares multiple ML algorithms simultaneously
- ✅ Auto-selects the best-performing model based on accuracy
- ✅ Handles spelling errors in symptom input using fuzzy matching
- ✅ Provides data visualizations including graphs and heatmaps
- ✅ Simple and intuitive symptom input interface

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas & NumPy | Data manipulation and processing |
| Scikit-learn | ML model training and evaluation |
| Matplotlib & Seaborn | Data visualization |
| Difflib | Fuzzy matching for symptom spelling |
| Jupyter Notebook | Development and experimentation |

---

## 🤖 Machine Learning Models

The following classifiers are trained, evaluated, and compared:

| Model | Description |
|---|---|
| Decision Tree | Rule-based splitting for classification |
| Naive Bayes | Probabilistic classifier based on Bayes' theorem |
| K-Nearest Neighbors (KNN) | Distance-based similarity classification |
| Logistic Regression | Linear model for binary/multi-class problems |

> The model with the highest accuracy on the test set is automatically selected for predictions.

---

## 📂 Dataset

- **Input features:** Symptoms (binary encoded columns)
- **Target output:** Disease labels
- **Format:** CSV file
- Preprocessing steps include encoding, null-value handling, and feature-vector construction

---

## ⚙️ How It Works

```
1. Load & preprocess the dataset
        ↓
2. Train multiple ML models
        ↓
3. Evaluate models using accuracy scores
        ↓
4. Auto-select the best model
        ↓
5. Accept user symptom input
        ↓
6. Convert input to a feature vector
        ↓
7. Output the predicted disease
```

---

## 📊 Output

- 🏥 **Predicted disease** based on entered symptoms
- 📈 **Accuracy comparison** of all trained models
- 📊 **Visualizations** — accuracy bar charts and symptom-disease heatmaps

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/disease-prediction-ml.git

# Navigate to the project directory
cd disease-prediction-ml

# Launch Jupyter Notebook
jupyter notebook
```

Open the main `.ipynb` file and run all cells. When prompted, enter your symptoms to receive a disease prediction.

---

## 🚧 Limitations

- Prediction quality depends heavily on the dataset used
- Heavy models (e.g., Random Forest, SVM) are excluded due to memory constraints
- Currently predicts only the single most probable disease
- Does not replace professional medical diagnosis

---

## 🔮 Future Improvements

- [ ] Integrate advanced ML models when resources allow (e.g., Random Forest, XGBoost)
- [ ] Use larger, real-world, and real-time datasets
- [ ] Build a web or mobile application interface
- [ ] Return multiple disease suggestions with probability scores
- [ ] Add multi-language support for broader accessibility

---

## 👨‍💻 Author

**Uday Mahajan**

If you found this project helpful, feel free to ⭐ star the repository and share your feedback!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
