# 🧠 Epileptic Seizure Detection using Support Vector Machine (SVM)

This repository contains the source code and dataset preprocessing for my Final Year Project (FYP) titled:  
**"A PERFORMANCE EVALUATION OF ENHANCING EPILEPTIC SEIZURE DETECTION USING SUPPORT VECTOR MACHINE"**

---

## 📌 Project Overview

The goal of this project is to detect epileptic seizures using EEG signal data by applying:
- **Time Domain** and **Frequency Domain** feature extraction
- **Support Vector Machine (SVM)** as the main machine learning classifier

This system classifies EEG signals into two classes:
- `0` — Non-Seizure
- `1` — Seizure

---

## 📁 Dataset

- **Dataset Name**: Epileptic Seizure Recognition Dataset  
- **Source**: [Kaggle - Chaditya95](https://www.kaggle.com/datasets/chaditya95/epileptic-seizures-dataset/data)  
- Each row represents an EEG signal sample containing 178 readings, and a label indicating the class.

---

## 🧪 Machine Learning Model

- **Model**: Support Vector Machine (SVM)  
- **Kernel**: Radial Basis Function (RBF)  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, Confusion Matrix

---

## ⚙️ Feature Extraction

### Time Domain Features:
- Mean
- Standard Deviation
- Skewness
- Kurtosis
- Root Mean Square (RMS)
- Signal Energy

### Frequency Domain Features:
- Maximum FFT Amplitude
- Spectral Centroid
- Spectral Entropy

These features were extracted from each EEG signal row before training the SVM model.

---

## 🧠 Tools & Technologies

- Python 3.x
- Jupyter Notebook
- NumPy, Pandas, Scikit-learn
- SciPy, Matplotlib, Seaborn

---

## 🚀 How to Run This Project

1. Clone this repo  
2. Make sure you have Jupyter Notebook and required libraries installed  
3. Run `main.ipynb` notebook step by step  
4. The notebook covers:
   - Data cleaning
   - Feature extraction
   - Model training
   - Evaluation & result visualization

---

## 👨‍💻 Author

**Adam Afiq**  
Final Year Student - Computer Network & Security  
Universiti Teknologi Malaysia (UTM)  
🔗 [LinkedIn Profile](www.linkedin.com/in/adam-afiq-230619151)
---

Feel free to star ⭐ this repo or connect with me if you find this helpful!
