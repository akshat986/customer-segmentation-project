# 🧠 Customer Segmentation using K-Means

This project demonstrates how to use unsupervised machine learning (K-Means Clustering) to segment customers based on their demographics and purchasing behavior.

---

## 📊 Dataset

**Mall\_Customers.csv** from Kaggle: [Link](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

**Features:**

- CustomerID
- Gender
- Age
- Annual Income (k\$)
- Spending Score (1-100)

---

## 📌 Objective

Identify different groups (clusters) of customers based on income, age, and spending score to better understand customer segments for targeted marketing.

---

## 🧪 Tools & Libraries

- Python
- Pandas, Matplotlib, Seaborn
- Scikit-learn (KMeans, StandardScaler)
- Google Colab

---

## 🛠️ Steps Involved

1. Data Cleaning & EDA
2. Data Visualization
3. Feature Scaling
4. Elbow Method to find optimal clusters
5. KMeans Clustering
6. Cluster Interpretation

---

## 🔍 Key Insights

- Customers can be segmented into 5 clear groups
- One group: High income + high spenders
- Another group: Low income + high spenders = marketing opportunity

---

## 📁 Folder Structure

```
customer-segmentation-project/
├── data/Mall_Customers.csv
├── segmentation.ipynb
├── segmentation.py
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python segmentation.py
```

Or open `segmentation.ipynb` in Google Colab for an interactive version.

---

## 📌 License

Dataset is under "Other" license on Kaggle.

---

## 👤 Author

Built as part of an internship learning project on customer analytics and ML.
