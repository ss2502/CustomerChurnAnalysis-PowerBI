Customer Churn Analysis Dashboard- **link - https://app.powerbi.com/groups/me/reports/1cf01430-f5d0-46e4-b141-279a74400ecf/ReportSection?experience=power-bi&redirectedFromSignup=1%3Fru%3Dhttps:%2F%2Fapp.powerbi.com%2Fgroups%2Fme%2Freports%2F1cf01430-f5d0-46e4-b141-279a74400ecf%2FReportSection%3Fexperience%3Dpower-bi%26redirectedFromSignup%3D1,1
**Welcome to the Customer Churn Analysis Dashboard project! This dashboard, created in Power BI, offers valuable insights into customer behavior, identifying potential churn risks and providing a comprehensive view of customer segments.

Project Overview
The project utilized Python to calculate churn percentages and customer segments, enhancing the analytical capabilities of the dashboard.

Python Code for Churn Calculation
The Python code involves data manipulation and churn analysis. It includes:

Importing necessary libraries
Reading the initial data from "data.csv"
Calculating the last purchase date for each customer
Identifying churned customers based on a defined churn threshold
Adding a 'Churned' column to the DataFrame
K-Means Clustering for Customer Segmentation
To segment customers, K-Means clustering was applied to Recency, Frequency, and Monetary (RFM) values. The process included:

Calculating RFM values
Standardizing features for K-Means
Determining the optimal number of clusters using the Elbow Method
Applying K-Means clustering to assign clusters to customers
Integration with Power BI
The generated customer segmentation data, including the 'Cluster' and 'Cluster Name' columns, was merged with the original dataset and saved as "customer_segmentation1.csv." This CSV file can be easily imported into Power BI for dashboard creation.

Instructions for Power BI Integration
Load the "customer_segmentation1.csv" file into Power BI.
Utilize the 'Cluster' and 'Cluster Name' columns for comprehensive customer segmentation analysis.
Leverage the 'Churned' column to identify customers at risk of churn.
Explore the interactive features of the dashboard to gain deeper insights into customer behavior.
Feel free to customize and expand upon this Power BI dashboard to suit your specific analytical needs. Happy analyzing!
