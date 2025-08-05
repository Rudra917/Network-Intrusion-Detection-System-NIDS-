# 🛡️ Network Intrusion Detection System (NIDS) using Machine Learning

This project is part of the **IBM Virtual Internship - Capstone Project**. It focuses on building an intelligent **Network Intrusion Detection System** that classifies network traffic as normal or malicious using machine learning techniques and deploys the model on **IBM Watson Studio**.

---

## 📌 Problem Statement

Modern network infrastructures are increasingly exposed to a wide range of cyber-attacks such as Denial of Service (DoS), Probing, Remote-to-Local (R2L), and User-to-Root (U2R). These attacks can compromise data integrity, service availability, and system confidentiality. The key challenge is to accurately distinguish between normal and malicious network traffic using large volumes of connection records and behavioral patterns, without relying on manual monitoring. Failure to do so can result in undetected intrusions and potential breaches across critical systems.

---

## 💡 Proposed Solution

- A machine learning-based intrusion detection system using the **NSL-KDD** dataset.
- Automated model training using **IBM Watson AutoAI**.
- Deployment of the trained model as a **REST API** using **IBM Cloud**.
- Capable of detecting **23 classes** of network traffic (attacks and normal).

---

## 🧰 Tools & Technologies

**Tools & Platforms:**
- 🟦 **IBM Cloud** (Mandatory)
- 🧠 **IBM Watson Studio** – for model development and deployment
- ☁️ **IBM Cloud Object Storage** – for dataset storage and handling

**Languages & APIs Supported:**

- cURL
- Java
- JavaScript
- Python
- Scala

The model was deployed as a **REST API**, which can be consumed using any of these languages.

**Dataset Used:**
- 📊 **NSL-KDD Dataset (KDDTrain+)**  
  Source: [Kaggle – NSL-KDD Dataset](https://www.kaggle.com/datasets/hassan06/nslkdd?select=KDDTrain%2B.txt)

---

## 📂 Dataset Description

- Dataset: **NSL-KDD** (`KDDTrain+`)
- Total features: 42 input features + 1 target label (`class`)
- Attack categories: DoS, Probe, R2L, U2R
- Total classes: 23 (e.g., normal, neptune, smurf, portsweep, etc.)

---

## ⚙️ Model Development Process

1. Loaded and preprocessed the NSL-KDD dataset
2. Encoded categorical variables
3. Scaled numerical features
4. Split data (80% training, 20% testing)
5. Trained multiple models using **IBM Watson AutoAI**
6. Selected the best-performing model (e.g., Snap Decision Tree Classifier)
7. Deployed model as REST API endpoint on IBM Cloud
8. Tested using real sample JSON input

---

## 📊 Model Results

> 📌 **Note:** Sample input data and output predictions have been included in the project presentation.  
> Please refer to the uploaded Pdf (`NIDS Project.pdf`) for detailed model testing and result visuals.

