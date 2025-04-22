# 🔍 Fake Job Posting Detection & Clustering

This project focuses on detecting fake job postings using supervised classification and uncovering hidden patterns through unsupervised clustering.

## 📁 Dataset

The dataset used contains various job post attributes such as title, description, company profile, and more. The target is to classify the job post as **real or fake**.

---

## 📌 Problem Statement

With the rise of online job platforms, fraudulent job postings have become common. The goal of this project is to:
- Classify job postings as **Real** or **Fake**
- Perform **clustering** to identify groupings of similar job posts
- Visualize insights using confusion matrices and clustering plots

---

## 🛠️ Methodology

### 🔷 Classification
- **Model Used**: Random Forest
- **Features**: Title length, Description length, Company Profile presence
- **Evaluation Metrics**: Accuracy, Precision, Recall, Confusion Matrix

### 🔷 Clustering
- **Algorithm Used**: K-Means
- **Preprocessing**: StandardScaler
- **Goal**: Discover natural clusters of job posts
- **Visualization**: Seaborn Pairplots

---

## 🧪 Results

| Metric      | Value     |
|-------------|-----------|
| Accuracy    | 50%       |
| Precision   | 62.5%     |
| Recall      | 41.7%     |

✅ Confusion matrix and clustering visualizations were generated and analyzed.


---


