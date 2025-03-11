# Customer-Segmentation-using-K-Means-and-DBSCAN

This project demonstrates customer segmentation using two popular clustering algorithms: K-Means and DBSCAN. 

**Dataset:**

The project utilizes the Online Retail dataset available at the UCI Machine Learning Repository. This dataset contains transactional data of an online retail store.

**Methodology:**

1. **Data Preprocessing:**
    - The dataset is loaded and cleaned.
    - Relevant features such as Total Bill Size, Purchase Interval Days, Most Common Location, and Top Item are engineered.
    - The features are scaled using StandardScaler for K-Means.

2. **K-Means Clustering:**
    - The K-Means algorithm is applied to segment customers based on their Total Bill Size.
    - The optimal number of clusters is determined (in this case, 3).
    - Clusters are analyzed based on average spend, top locations, and top items purchased.

3. **DBSCAN Clustering:**
    - The DBSCAN algorithm is applied using Total Bill Size and Purchase Interval Days as features.
    - Clusters and noise points are identified.
    - Cluster characteristics are analyzed based on average total bill and average purchase interval.

**Results:**

The project provides insights into different customer segments based on their purchasing behavior. The K-Means clustering reveals distinct groups based on spending habits, while DBSCAN identifies clusters based on spending and purchase frequency.

**Usage:**

1. Clone the repository.
2. Install the required libraries: pandas, scikit-learn, matplotlib.
3. Run the Jupyter Notebook to execute the code and view the results.

**Note:**

- The number of clusters for K-Means and the parameters for DBSCAN can be adjusted for further analysis.
- The project can be extended by incorporating other features and exploring different clustering algorithms.
