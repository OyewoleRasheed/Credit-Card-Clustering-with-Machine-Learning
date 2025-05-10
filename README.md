# 💳 Credit Card Clustering with Machine Learning

## 📌 Overview

This project performs **unsupervised clustering** on credit card customer data to segment users based on their financial behavior. By analyzing features like balance, purchases, and credit limit, we aim to identify distinct customer groups that can inform targeted marketing strategies and financial services.

---

## 📂 Dataset

* **Source**: The dataset is available from the original article.
* **File**: `CC GENERAL.csv`
* **Key Features**:

  * `BALANCE`: Average balance during the period
  * `PURCHASES`: Total purchase amount
  * `CREDIT_LIMIT`: Credit limit assigned to the customer.

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Plotly

---

## 🧪 Methodology

1. **Data Preprocessing**:

   * Load the dataset using Pandas.
   * Handle missing values by dropping rows with null entries.

2. **Feature Selection**:

   * Select relevant features: `BALANCE`, `PURCHASES`, and `CREDIT_LIMIT`.

3. **Feature Scaling**:

   * Apply `MinMaxScaler` to normalize the data between 0 and 1.

4. **Clustering**:

   * Use `KMeans` clustering with a predefined number of clusters (e.g., 5).
   * Assign cluster labels to each customer.

5. **Visualization**:

   * Create a 3D scatter plot using Plotly to visualize the clusters.([thecleverprogrammer][2])

---

## 📊 Results

The clustering analysis segments customers into distinct groups based on their financial behaviors. The 3D visualization provides an intuitive understanding of how customers are grouped, which can be valuable for business decision-making.

---

## 📈 Visualization

I used a 3d scatterplot to visualize the clusters

---

## 📌 Conclusion

This project demonstrates how unsupervised machine learning techniques like KMeans clustering can be applied to real-world financial data to uncover meaningful customer segments. Such insights can drive personalized marketing and improve customer relationship management.

---

## 📚 References

* Original Article: [Credit Card Clustering with Machine Learning](https://thecleverprogrammer.com/2022/10/03/credit-card-clustering-with-machine-learning/)
