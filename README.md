# Customer-Clustering-KMeans  

This project demonstrates customer segmentation using the **K-Means Clustering** algorithm on the **Mall Customers** dataset. The objective is to group customers of a retail store based on their purchase history.  

---

## 🛠️ Features  

- **Data Preprocessing:** Selection and standardization of relevant features (`Age`, `Annual Income`, and `Spending Score`).  
- **Elbow Method:** Determines the optimal number of clusters by analyzing the inertia.  
- **K-Means Clustering:** Groups customers into clusters with similar purchasing behaviors.  
- **Visualization:** Visualizes the data before and after clustering.  
- **Evaluation:** Calculates the silhouette score to assess cluster quality.  

---

## 📊 Dataset  

**Dataset Name:** Mall_Customers.csv  
**Source:** [Kaggle - Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  

The dataset contains the following columns:  
- **CustomerID:** Unique identifier for each customer.  
- **Gender:** Gender of the customer (Male/Female).  
- **Age:** Age of the customer.  
- **Annual Income (k$):** Annual income of the customer in thousand dollars.  
- **Spending Score (1-100):** A score assigned by the mall based on customer behavior.  

---

## 🔍 Steps in the Project  

1. **Data Loading:**  
   - Load the `Mall_Customers.csv` dataset and preview the data.  

2. **Preprocessing:**  
   - Select relevant features for clustering: `Age`, `Annual Income`, and `Spending Score`.  
   - Standardize these features using `StandardScaler` for optimal clustering performance.  

3. **Elbow Method:**  
   - Analyze the inertia values for 1-14 clusters and identify the optimal number of clusters.  

4. **K-Means Clustering:**  
   - Apply the K-Means algorithm using the optimal number of clusters.  
   - Assign cluster labels to each customer.  

5. **Cluster Visualization:**  
   - Visualize the clusters using the first two dimensions of the standardized data.  
   - Highlight cluster centroids.  

6. **Evaluation:**  
   - Calculate the silhouette score to evaluate the quality of clustering.  

---

## 📈 Results  

- **Cluster Centroids:**  
  The centroids represent the average feature values for each cluster.  

- **Silhouette Score:**  
  The calculated silhouette score is **0.4085**, indicating moderately well-separated clusters.  

---

## 🔧 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/niamat-sirrou/Customer-Clustering-KMeans.git
   cd Customer-Clustering-KMeans
