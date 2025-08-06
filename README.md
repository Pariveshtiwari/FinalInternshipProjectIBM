# Predictive Maintenance of Industrial Machinery

## 📌 Project Overview
This project was developed as part of the **IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies**, organized by **Edunet Foundation** in collaboration with **AICTE**.  
The goal is to create a **predictive maintenance model** that anticipates machinery failures before they occur, enabling **proactive maintenance**, reducing **downtime**, and lowering **operational costs**.

---

## 🔍 Problem Statement
**Problem Statement No. 39**  
Develop a **predictive maintenance model** for a fleet of industrial machines to anticipate failures before they occur.  
The model analyzes **sensor data** from machinery to identify patterns that precede a failure and classify the type of failure such as:
- Tool Wear
- Heat Dissipation Failure
- Power Failure
- Overstrain Failure
- Random Failure

---

## 🛠 Technologies & Tools
- IBM Cloud Lite Services:
  - Watson Studio
  - AutoAI (for model building & deployment)
  - IBM Cloud Object Storage
- Python (for data preprocessing)
- Dataset: [Predictive Maintenance Dataset (Kaggle)](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

---

## 📂 Dataset Details
The dataset contains real-time **operational data** of industrial machines, including:
- Air Temperature
- Process Temperature
- Rotational Speed
- Torque
- Tool Wear
- Failure Type (Target Variable)

---

## ⚙ Approach
1. **Data Acquisition** – Downloaded dataset from Kaggle and uploaded to IBM Cloud Object Storage.
2. **Data Preprocessing** – Cleaned and formatted dataset for analysis.
3. **AutoAI Experiment** – Leveraged IBM AutoAI to:
   - Automatically train multiple models
   - Perform hyperparameter optimization
   - Select the best performing classification model
4. **Model Deployment** – Deployed the best model on IBM Watson Studio for real-time prediction.
5. **Evaluation** – Assessed model performance using metrics like **Accuracy**, **F1 Score**, and **Confusion Matrix**.

---

## ✅ Features
- Predicts **machine failure type** based on sensor data.
- Uses **cloud-based AutoAI** for model creation and deployment.
- No manual coding of ML algorithms required.





