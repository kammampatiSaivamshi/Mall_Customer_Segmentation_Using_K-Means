## 🛍️ Mall Customer Segmentation Using K-Means

### 📌 Overview

Customer segmentation is the practice of dividing a customer base into groups of individuals that are similar in specific ways. This project uses the **K-Means clustering algorithm** to segment mall customers based on their demographics and spending habits.

### 🎯 Objective

To apply unsupervised machine learning (K-Means Clustering) to identify distinct customer segments based on:

* Annual Income
* Spending Score
* Age

This helps mall marketers to understand customer groups and tailor their strategies accordingly.

---

### 📂 Dataset

**Source:** `Mall_Customers.csv`
This dataset contains the following features:

| Column Name              | Description                                                               |
| ------------------------ | ------------------------------------------------------------------------- |
| `CustomerID`             | Unique ID for each customer                                               |
| `Gender`                 | Gender of the customer                                                    |
| `Age`                    | Age of the customer                                                       |
| `Annual Income (k$)`     | Annual income in thousands of dollars                                     |
| `Spending Score (1-100)` | Score assigned by the mall based on customer behavior and spending nature |

---

### ⚙️ Project Workflow

1. **Data Loading and Exploration**

   * Basic statistics
   * Missing values check
   * Distribution plots

2. **Feature Selection & Scaling**

   * Selection of relevant features for clustering
   * Standardization for fair comparison

3. **K-Means Clustering**

   * Elbow Method to determine optimal number of clusters
   * Model training with KMeans
   * Cluster assignment

4. **Visualization**

   * 2D Scatter plots of clusters
   * Cluster centroids
   * Comparison based on gender and age

---

### 📊 Key Results

* Optimal clusters determined using Elbow Method
* Visualized 3–5 customer groups based on income and spending score
* Identified customer types:

  * High Income & High Spending
  * Low Income & Low Spending
  * High Income & Low Spending
  * Young age group with medium spending, etc.

---

### 📌 Technologies Used

* Python 🐍
* Libraries:

  * `pandas`, `numpy` – data manipulation
  * `matplotlib`, `seaborn` – visualization
  * `scikit-learn` – clustering & preprocessing

---

### 📎 Future Scope

* Use **Hierarchical Clustering** for comparison
* Add **RFM (Recency, Frequency, Monetary)** analysis
* Deploy as a Streamlit or Flask app for interactive segmentation

---

### ✅ How to Run

1. Clone the repository or download the notebook
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter Notebook:

   ```
   jupyter notebook Mall_Customer_Segmentation_Using_K-Means.ipynb
   ```

---

### 🙋‍♂️ Author

**Vamshi K**
*Aspiring Data Scientist*
📫 Reach me on [LinkedIn](https://www.linkedin.com)

