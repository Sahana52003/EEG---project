# 🧠 EEG-Based Epileptic Seizure Detection Using Machine Learning

This project focuses on detecting **epileptic seizures** from **EEG (Electroencephalogram)** signals using **machine learning models**. It aims to automatically identify abnormal brain activity to support faster diagnosis and real-time monitoring of epileptic patients.

---

## 🌍 Overview
Epilepsy is a neurological disorder that causes sudden and recurrent seizures due to abnormal brain activity.  
Manual EEG analysis is time-consuming and requires expert knowledge.  
This project applies **classical machine learning** techniques to automate seizure detection, improving accuracy and reducing the workload for clinicians.

---

## 📊 Dataset
The dataset used in this project is the ** EEG Database**), which contains EEG recordings from pediatric patients.  
EEG signals were preprocessed, filtered, and segmented into seizure and non-seizure periods.

---

## ⚙️ Methodology
1. **Data Preprocessing**
   - Bandpass filtering (0.5–40 Hz)  
   - Artifact removal  
   - Segmentation into short time windows  

2. **Feature Extraction**
   - Time-domain: mean, variance, Hjorth parameters  
   - Frequency-domain: spectral power across delta, theta, alpha, beta, and gamma bands  
 

3. **Model Training**
   - Classical ML models: **Support Vector Machine (SVM)**, **Random Forest**  

4. **Evaluation Metrics**
   - Accuracy  
   - Precision, Recall, F1-score  

---

## 📈 Results
| Model | Dataset | Accuracy | F1-Score |
|--------|----------|-----------|-----------|
| SVM | CHB-MIT | 95.2% | 0.94 |
| Random Forest | CHB-MIT | 94.5% | 0.93 |

These results demonstrate strong performance in distinguishing seizure and non-seizure EEG segments.

---

## 💻 Installation
Clone the repository:
```bash
git clone https://github.com/Sahana52003/EEG---project.git
cd EEG---project
