# E-commerce-Customers-Segmentation
### Overview
This project involves analyzing customer transactional data to segment customers based on their behaviors and demographics. We use K-Means clustering to identify distinct customer segments and provide insights into each segment to enhance marketing strategies, especially in coupon distribution.

### Data Description
The dataset consists of multiple sheets in an Excel file:

customers: Contains customer information.
genders: Contains gender information.
cities: Contains city information.
transactions: Contains transaction records.
branches: Contains branch information.
merchants: Contains merchant information.

### project steps
#### 1. Data Loading and Preprocessing
Load data from the Excel file.
Merge relevant sheets to create a comprehensive dataset.
Handle missing values, particularly in burn_date.
Encode categorical variables into numeric values.

#### 2. Feature Selection
Select relevant features for clustering, including:

Customer demographics (e.g., gender, city)
Transactional features (e.g., coupon usage, transaction status)

#### 3. Clustering
Elbow Method: Used to determine the optimal number of clusters by plotting inertia values.
K-Means Clustering: Applied to segment customers into clusters.
Add Cluster Labels: Assign cluster labels to the dataset.

#### 4. Segment Analysis
Analyze each segment based on:

Number of customers
Most frequent values in categorical variables
Average values in numeric variables.

#### 5. Results and Visualization
Plot the Elbow Method to choose the number of clusters.
Save the clustered data to an Excel file for further analysis.
