❤️ AI-Based Heart Disease Diagnosis & Decision Support System

An AI-based research project for heart disease prediction, 12-lead ECG classification, and ECG signal processing using machine learning and deep learning.

Based on the research paper:

Simegn GL, Gebeyehu WB, Degu MZ. Computer-Aided Decision Support System for Diagnosis of Heart Diseases. Research Reports in Clinical Cardiology. 2022;13:39–54.

Paper: https://www.dovepress.com/computer-aided-decision-support-system-for-diagnosis-of-heart-diseases-peer-reviewed-fulltext-article-RRCC

📁 Repository Structure

.
├── 12_Lead ECG Signal multiclassification.ipynb
├── ECG processor2.ipynb
├── Heart Disease prediction.ipynb
├── Heart disease prediction_Neural network.ipynb
├── heart12.csv
└── README.md

🎯 Project Overview

The project explores three main areas:

Heart Disease Prediction using machine learning

12-Lead ECG Classification using deep learning

ECG Signal Processing for waveform analysis

1. Heart Disease Prediction

Heart Disease prediction.ipynb

Uses clinical/patient information to predict heart disease. The research evaluates models including:

Random Forest

XGBoost

2. Neural Network Prediction

Heart disease prediction_Neural network.ipynb

Uses an Artificial Neural Network (ANN) for binary heart disease classification.

Reported ANN architecture:

13 Input Neurons
       ↓
11 Hidden Neurons
       ↓
1 Output Neuron

3. 12-Lead ECG Classification

12_Lead ECG Signal multiclassification.ipynb

Uses a 1D Convolutional Neural Network (CNN/Conv1D) to classify 12-lead ECG signals into multiple cardiac conditions. The research reports classification across 18 conditions.

4. ECG Signal Processing

ECG processor2.ipynb

Processes ECG signals and analyzes important waveform characteristics, including:

P wave

QRS complex

T wave

R peaks

Amplitude

Duration

Heart rate

📊 Results Reported in the Paper

Model / Task

Reported Result

Random Forest

ROC-AUC = 1.00

XGBoost

ROC-AUC ≈ 0.98

ANN

ROC-AUC ≈ 0.95

12-Lead ECG CNN

Accuracy ≈ 93.27%

These are results reported by the original research paper and should not be interpreted as guaranteed performance on new clinical data.

🛠️ Technologies

Python

Jupyter Notebook

NumPy

Pandas

Scikit-learn

XGBoost

TensorFlow / Keras

SciPy

Matplotlib

Seaborn

▶️ How to Run

Clone the repository:

git clone https://github.com/gsimegn/Computer-aided-diagnosis-system-for-heart-disease

Install common dependencies:

pip install numpy pandas matplotlib seaborn scipy scikit-learn xgboost tensorflow jupyter

Start Jupyter:

jupyter notebook

Then open any of the four notebooks.

The ECG classification notebook requires the ECG data expected by the notebook. The repository shown here contains heart12.csv for the heart-disease prediction work.

📚 Dataset

heart12.csv is used for the heart disease prediction notebooks.

The research paper also describes a larger collection of ECG recordings used for the 12-lead ECG classification experiments.

⚠️ Disclaimer

This project is for research and educational purposes only. It is not a medical device and should not be used to diagnose, treat, or make clinical decisions about patients. The reported research results do not guarantee real-world clinical performance.

📖 Citation

Simegn GL, Gebeyehu WB, Degu MZ.
Computer-Aided Decision Support System for Diagnosis of Heart Diseases.
Research Reports in Clinical Cardiology. 2022;13:39–54.
doi:10.2147/RRCC.S366380
