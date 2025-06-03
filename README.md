# 📊 Clustering Instagram Users Based on Visit Patterns and Spending Behavior

This project demonstrates the application of **unsupervised machine learning techniques** to segment Instagram users based on their **visit frequency** and **spending rank**. Using real-world behavioral data, we explore various clustering algorithms to uncover meaningful user segments that can support marketing strategies, user engagement, and product personalization.

---

## 🔍 Introduction

Social media platforms like Instagram collect rich behavioral data, including user activity and preferences. Understanding this data can help platforms and businesses:
- Personalize content and advertisements
- Improve user engagement
- Discover customer personas

In this project, we use clustering techniques to analyze **Instagram visit scores** and **spending behavior** to identify distinct user groups.

---

## 🎯 Objective

- Group users into meaningful clusters based on behavioral patterns
- Compare multiple clustering algorithms to evaluate their performance
- Visualize and interpret the resulting clusters for actionable insights

---

## 🛠️ Clustering Algorithms Used

The following clustering methods were implemented and compared:

- ✅ **K-Means Clustering**
- ✅ **K-Medoids Clustering (PAM)**
- ✅ **Agglomerative Clustering – Single Linkage**
- ✅ **Agglomerative Clustering – Complete Linkage**

---

## 📁 Dataset Description

The dataset includes two key behavioral features for each user:

| Feature               | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `Instagram_visit_score` | Numerical score indicating how frequently a user visits Instagram          |
| `Spending_rank (0–100)` | Normalized value (0–100) representing a user’s relative spending behavior |

---

## 📈 Visualizations

The project includes the following visual tools to support analysis:

- Histograms and KDE plots for feature distribution
- Scatter plots of clustered data
- Boxplots to show spread and outliers
- Cluster visualizations for each algorithm

---

## 📌 Key Findings

- **Bimodal distributions** were observed in both Instagram visit scores and spending ranks.
- **Distinct clusters** emerged, including high-spend/high-visit users and low-engagement users.
- K-Means and Agglomerative Clustering (Complete Linkage) produced the most interpretable clusters.
- Clear **user personas** were derived, useful for marketing or platform optimization.

---

## 📦 Requirements

To run this project, install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
