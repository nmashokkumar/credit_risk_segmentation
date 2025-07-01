# 📊 Credit Risk Customer Segmentation using KMeans Clustering

This project applies **KMeans Clustering and PCA for dimensionality reduction** to segment credit card customers based on payment behaviors, credit limits, and bill payment patterns. This helps in **understanding customer risk profiles to aid credit risk management.**

---

## 🟩 Project Objectives

* Perform **EDA and Statistical Analysis**
* Scale features for clustering
* Use **Elbow Method to find optimal `k`**
* Apply **KMeans Clustering**
* Visualize clusters using **PCA (2D)**
* Profile and interpret customer segments

---

## 📂 Dataset

Used the **Taiwan Credit Card Default Dataset** with features:

* `LIMIT_BAL` (Credit Limit)
* `AGE`, `SEX`, `EDUCATION`, `MARRIAGE`
* Payment history: `PAY_0` to `PAY_6`
* Bill amounts: `BILL_AMT1`, `BILL_AMT6`
* Payment amounts: `PAY_AMT1`, `PAY_AMT6`
* Target: `default payment next month` (for reference only; not used for clustering)

---

## ⚙️ Methodology

* Preprocessing: Checked skewness, outliers using Z-score, scaled data with `StandardScaler`.
* Elbow Method: Determined optimal clusters (`k=3`).
* KMeans Clustering: Applied with `k=3`.
* PCA Visualization: Reduced to 2 components for clear visualization.

---

## 🎨 Cluster Visualization



### Color Legend:

* 🟢 Green: **Low Risk Customers**
* 🟡 Yellow: **Medium Risk Customers**
* 🟣 Purple: **High Risk Customers**

---

## 📈 Cluster Insights

**Low Risk (Green):**

* Higher credit limits
* Timely payments
* Low outstanding bills

**Medium Risk (Yellow):**

* Moderate credit limits
* Occasional delays
* Mid-range bills

**High Risk (Purple):**

* Lower credit limits
* Frequent payment delays
* Higher outstanding bills

---

## 🚀 Why This Matters

* Helps banks and NBFCs **target customer segments effectively**
* Identify low-risk customers for premium products
* Identify high-risk customers for intervention or credit counseling
* Supports **data-driven credit risk management strategies**

---

## 🛠️ Tech Stack

* Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn)
* Jupyter Notebook

---

## ✍️ Author

**Ashok Kumar**
*Data Science Aspirant | Passionate about Statistics & ML*
[LinkedIn](https://www.linkedin.com/in/nmashokkumar/) | [GitHub](https://github.com/nmashokkumar)

---

## 📌 Usage

* Clone this repo
* Run `Credit_Risk_Clustering.ipynb`
* Analyze and modify for deeper analysis or deployment

---

*If you find this project helpful, feel free to **star ⭐ the repo!***

---

**## 🚩 Next Steps**

* Extend to supervised models using `default payment next month`
* Build an end-to-end **Credit Risk Dashboard**
* Explore advanced clustering (DBSCAN, Hierarchical Clustering)
