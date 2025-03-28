**Enhancing Marketing Strategies through Data-Driven Customer Profiling**

**Project Overview**

This project utilizes unsupervised clustering techniques on customer data from a groceries firm to segment customers based on shared characteristics. 

The goal is to enhance customer engagement by customizing product offerings and marketing strategies for different customer segments.

**Project Description**

**Customer Segmentation:** Categorizes customers into groups based on similarities within each cluster, allowing businesses to address diverse customer needs effectively.

**Customized Marketing:** Enables tailored product modifications and marketing strategies for each customer segment.

**Dataset**

The dataset used is publicly available and contains customer records from a groceries firm.

**Steps**

1. Data Cleaning: Handling missing values, parsing dates, and creating new features like customer age, spending, and family size.

2. Data Preprocessing: Label encoding categorical variables, scaling features, and creating a copy of the data for analysis.

3. Dimensionality Reduction: Applied PCA to reduce the dataset's dimensionality to 3 components for easier analysis and visualization.

4. Clustering: Used K-Means and Agglomerative Clustering to segment customers into 4 distinct groups based on their features.

5. Evaluating Models: Assessed the clustering performance and visualized the clusters.

6. Profiling: Analyzed the income, spending habits, and campaign responses of each cluster to help refine marketing strategies.

**Key Findings**

> Income vs. Spending Profile: Grouped customers into high spending, average income; high spending, low income; high spending, high income; and low spending, low income.

> Spending Distribution: Cluster 2 (high income, high spending) and Cluster 0 (high spending, average income) were the highest spenders.

> Campaign Response: Low overall campaign response, suggesting a need for more targeted campaigns.

> Deals Purchased: Clusters 0 and 1 showed a strong interest in deals, while Cluster 2 (high spenders) showed little interest.

**Conclusion**

This project successfully segmented customers and profiled them based on key factors such as family structure, income, and spending habits. 

The insights gained can help businesses refine their marketing strategies and enhance customer engagement.
