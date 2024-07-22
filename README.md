# Customer Segmentation Using RFM Clustering for Retail Clothing

## Project Overview
This project focuses on customer segmentation for a retail startup in the clothing industry. By leveraging Recency, Frequency, and Monetary (RFM) analysis and clustering algorithms, we aim to identify distinct customer segments and provide actionable insights into their purchasing behavior. These insights can help the business tailor marketing strategies, improve customer engagement, and boost overall sales.

<img width="698" alt="Screenshot 2024-07-22 at 11 17 10 AM" src="https://github.com/user-attachments/assets/f768e612-c51b-4aef-919a-d3060ff70425">


## Introduction
Customer segmentation is a crucial aspect of marketing strategy, allowing businesses to understand their customer base better and target different segments with tailored approaches. This project employs RFM analysis combined with clustering techniques to categorize customers based on their purchasing behavior in the clothing category.

## Data Description
The dataset used in this project contains transactional retail data. Key columns include:

Transaction_ID
Customer_ID
City
State
Age
Gender
Income
Customer_Segment
Date
Total_Purchases
Amount
Total_Amount
Product_Category
Product_Brand
Product_Type
Shipping_Method
Payment_Method
Order_Status
products

## Methodology

### Data Preprocessing
- Filtering Data: Extract transactions related to the 'Clothing' product category.
- Handling Missing Values: Address missing values in the dataset.
- Feature Engineering: Compute Recency, Frequency, and Monetary values for each customer.

### RFM Analysis
Assign scores to each customer based on their recency, frequency, and monetary values according to defined intervals.

### Clustering
- Scaling: Apply Standard scaling to the RFM values.
- Algorithm: Use K-Means clustering to segment customers into different groups.
  
### Segment Profiling
Interpret the characteristics of each cluster to understand customer behavior:

- High-Value Customers: High 'Monetary' and 'Frequency' values, low 'Recency'.
- Loyal Customers: High 'Frequency' and moderate 'Monetary' values.
- At-Risk Customers: High 'Recency' values but previously had high 'Monetary' and 'Frequency' values.
- New Customers: Low 'Frequency' and 'Monetary' values, low 'Recency'.

### Results
The clustering results reveal distinct customer segments with unique purchasing behaviors. These insights help in identifying high-value customers, loyal customers, at-risk customers, and new customers.

## Conclusion
By leveraging RFM analysis and clustering techniques, this project provides valuable insights into customer segmentation for a retail clothing startup. These insights can guide marketing strategies, enhance customer engagement, and ultimately drive sales growth.
