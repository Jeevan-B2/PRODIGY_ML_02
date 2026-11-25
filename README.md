# Prodigy InfoTech - Machine Learning Internship

## Task 02: Customer Segmentation using K-Means Clustering

### 📌 Objective
Create a K-means clustering algorithm to group customers of a retail store based on their purchase history (Annual Income and Spending Score).

### 📊 Dataset
The dataset used is the [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) from Kaggle.

### 🛠️ Tools & Technologies
*   **Python**
*   **Google Colab**
*   **Pandas** (Data Manipulation)
*   **Scikit-Learn** (Machine Learning)
*   **Matplotlib** (Data Visualization)

### 🧠 Approach
1.  **Data Loading:** Loaded the `Mall_Customers.csv` dataset.
2.  **Feature Selection:** Selected `Annual Income (k$)` and `Spending Score (1-100)` as the two features for clustering.
3.  **The Elbow Method:** Iterated through cluster numbers 1 to 10, calculated the Within-Cluster Sum of Squares (WCSS), and plotted the results. The graph showed an "elbow" at K=5, indicating 5 is the optimal number of clusters.
4.  **Model Training:** Trained a K-Means model with `n_clusters=5`.
5.  **Visualization:** Plotted the 5 clusters with distinct colors and marked the centroids with yellow 'X' markers.

### 📈 Results & Business Insights
The model successfully segmented the mall's customers into 5 distinct groups:
*   **VIPs / Target:** High Income, High Spending (Green)
*   **Careful:** High Income, Low Spending (Blue)
*   **Standard:** Average Income, Average Spending (Red)
*   **Impulse:** Low Income, High Spending (Magenta)
*   **Frugal:** Low Income, Low Spending (Cyan)

This segmentation allows the mall to create highly targeted marketing campaigns for each specific group.
