# 🌐 Network Traffic Classification using Machine Learning

An unsupervised machine learning project that classifies network traffic flows using real-world TCP `.netflow` data. Built during an internship under Prof. Sriram Natarajan at UT Dallas.

---

## 🧠 Project Overview

This project applies clustering techniques to analyze and classify network traffic. The dataset consists of network flow summaries captured from TCP connections. The primary goal is to train an unsupervised model to distinguish between two different types of application-layer protocols without using labeled data.

The model is trained on one hour of unlabeled data and evaluated on two separate labeled test sets, using precision and recall due to the imbalanced nature of the classes.

---

## 🚀 Features

- Load and process `.netflow` files representing TCP flow summaries
- Engineer features such as duration, byte/packet counts, and concurrency
- Use K-Means clustering to classify traffic flows
- Evaluate model performance on labeled test sets using precision, recall, and confusion matrix
- Visualize results and analyze cluster behavior

---

## 🛠️ Tech Stack

- **Python**
- **Pandas** – data loading and feature manipulation
- **NumPy** – numerical computation
- **scikit-learn** – K-Means, evaluation metrics, preprocessing
- **Jupyter Notebook** – interactive development and analysis

---

## 📁 Getting Started

### 1. Clone the repository
```sh
git clone https://github.com/Raghav2128/network-traffic-classification-ml.git
```
### 2. Install Dependencies
```sh
pip install -r requirements.txt
```
### 3. Run the notebook
```sh
jupyter notebook networking_team.ipynb
```
