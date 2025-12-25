# Customer-Segmentation-Analysis-RFM-Marketing-Recommendations-using-K-Means-Clustering
This project implements K-Means clustering and RFM analysis to segment customers by behavior. Using Silhouette scores for optimization, I identified 7 distinct groups, including high-value "Whale" outliers and "At-Risk" segments. The result is a data-driven roadmap for targeted marketing

**Key Features**

-RFM Extraction: Engineered features for Recency, Frequency, and Monetary value from raw logs.

-K-Means Clustering: Implemented unsupervised learning to group customers by behavior.

-Optimization: Used the Elbow Method and Silhouette Score to determine the ideal number of clusters ($k=4$).

-Outlier Handling: Separated extreme "Whales" and high-frequency outliers (labeled -1, -2, -3) from standard clusters to prevent data skewing.

-Strategic Labeling: Translated numeric clusters into marketing segments (e.g., Champions, At-Risk, Loyalists).

**Technical Stack**
Language: Python
Data Manipulation: Pandas, NumPy
Machine Learning: Scikit-learn (StandardScaler, KMeans)
Visualization: Matplotlib, Seaborn

