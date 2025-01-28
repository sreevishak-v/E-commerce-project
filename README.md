
# E-commerce-project


## Project Overview
This project involves analyzing an eCommerce dataset to derive insights, build a lookalike model, and perform customer segmentation. The tasks aim to demonstrate data analysis, machine learning, and business intelligence skills to improve customer understanding and optimize business strategies.

## Dataset Description
The project uses three datasets:

### 1. Customers.csv

Contains customer profile information:

- CustomerID: Unique identifier for each customer.

- CustomerName: Name of the customer.

- Region: Geographic region of the customer.

- SignupDate: Date when the customer signed up


### 2. Products.csv
Contains product information:

- ProductID: Unique identifier for each product.

- ProductName: Name of the product.

- Category: Product category.

- Price: Price of the product in USD.
### Transactions.csv

Contains transaction details:

- TransactionID: Unique identifier for each transaction.

- CustomerID: ID of the customer who made the transaction.

- ProductID: ID of the product sold.

- TransactionDate: Date of the transaction.

- Quantity: Quantity of the product purchased.

- TotalValue: Total value of the transaction.
 
## Tasks and Deliverables
 ### Task 1: Exploratory Data Analysis (EDA)

- Objective: Perform EDA to understand customer behavior and transaction trends.

### Task 2: Lookalike Model
- Objective: Build a model to recommend 3 similar customers for the first 20 customers based on profile and transaction data.


### Task 3: Customer Segmentation/Clustering

-  Objective: Segment customers into distinct groups using clustering techniques.


### Clustering Metrics and Results
  - Number of Clusters: 10

- Davies-Bouldin Index (DB Index): 0.8928

- Silhouette Score: 0.3781

Summary: Customers were segmented into 10 distinct groups based on transaction and profile features, enabling targeted marketing and business optimization strategies.

### Technologies Used

Programming Language: Python

- Libraries:

      pandas and numpy: Data manipulation and analysis.

- scikit-learn: Machine learning algorithms for clustering and similarity computation.

-  matplotlib and seaborn: Data visualization.

### How to Run the Project

#### 1. Clone the repository:
```bash
  git clone <https://github.com/sreevishak-v/E-commerce-project.git>
```
#### 2. Run each task:

Task 1: Open the EDA  notebook and execute.

Task 2: Run the Lookalike Model script.

Task 3: Execute the Clustering script.
 
 (Reports as pdf format also upladed)
