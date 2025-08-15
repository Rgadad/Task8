# Task8
K-Means Clustering — Mall Customer Segmentation
📌 Objective

Perform unsupervised learning using K-Means clustering to segment mall customers based on their annual income and spending behavior.

🛠 Tools & Libraries

* Python

* Pandas → Data handling

* Matplotlib → Data visualization

* Scikit-learn → K-Means clustering, evaluation metrics

📊 Dataset

* Mall_Customers.csv

* Rows: 200

* Columns:

CustomerID — Unique customer ID

Gender — Male/Female

Age — Customer age in years

Annual Income (k$) — Annual income in $1000 units

Spending Score (1-100) — Score assigned based on spending habits

🚀 Steps Followed

* Load Dataset
Used Pandas to read and inspect the data.

* Feature Selection
Selected Annual Income and Spending Score for clustering.

* Elbow Method
Determined optimal number of clusters (K) by plotting WCSS vs K.

* K-Means Clustering

* Applied K-Means with optimal K.

* Assigned cluster labels to each customer.

Visualization

* Plotted customer segments in 2D.

* Marked centroids with yellow stars.

Evaluation
Calculated Silhouette Score to assess clustering quality.

📈 Results

* Optimal Clusters (K): Determined from Elbow Curve

* Silhouette Score: Closer to 1 indicates better clustering

* Customers grouped into distinct segments based on spending and income.

🎯 Insights

* Identifies high-income high-spending customers (premium segment).

* Detects budget-conscious customers.

* Helps target marketing strategies effectively.
