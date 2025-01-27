Objective
The notebook focuses on analyzing customer, product, and transaction data to derive actionable business insights. Techniques include customer segmentation, similarity analysis, and clustering.

Steps and Key Findings
Data Loading and Validation

Datasets (Customers, Products, Transactions) were loaded and verified for consistency.
No missing values were found, ensuring data completeness.
Exploratory Data Analysis (EDA)

Total Sales by Region:
Regions like South America and Asia showed significant sales contributions.
Sales Distribution by Product Category:
Certain categories, like Electronics and Books, dominated the sales.
Customer Lookalike Analysis

Customers were grouped based on total spending, quantity purchased, and average product price.
Cosine similarity was used to identify similar customers.
Output:
Example: Customer C0001 is most similar to C0103 with a similarity score of 0.997.
Insight: This enables personalized marketing by identifying customers with similar purchasing behaviors.
Clustering for Customer Segmentation

KMeans clustering grouped customers based on spending patterns.
The Elbow Method suggested an optimal cluster count (e.g., 4).
Davies-Bouldin Index (~0.57) confirmed good cluster separation.
Insight: Cluster-based strategies (e.g., premium vs. budget shoppers) can enhance targeting.
Summary Statistics

Product Prices:
Average price: 267.55, Maximum: 497.76.
Transaction Values:
Average transaction value: ~690, with large variability indicating diverse customer spending patterns.
Business Insights
Customer Lookalikes:

Enables targeted promotions by identifying similar customers.
Example: Tailored email campaigns or loyalty programs.
Customer Segmentation:

Clusters help differentiate high-value and low-value customers.
Example: Focus premium services on high-spending clusters.
Regional Sales Analysis:

Regions like South America contribute heavily to total sales.
Example: Optimize inventory allocation for high-performing regions.
Category Performance:

Categories like Electronics and Books dominate.
Example: Expand inventory or marketing for these categories.
Deliverables
Lookalike customer analysis saved in BHAVNESH_SHARMA_Lookalike.csv.
Clustering results saved in BHAVNESH_SHARMA_Clustering.csv.
