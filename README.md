# E-commerce Customer Segmentation using Machine Learning

## Project Overview
This project is developed as part of the MCA Minor Project.
The objective of this project is to analyze e-commerce customer behavior using transactional data and segment customers into meaningful groups.

Customer segmentation helps businesses understand different types of customers and design targeted marketing strategies.
In this project, RFM (Recency, Frequency, Monetary) analysis and K-Means clustering are used to group customers based on purchasing patterns.

The project is implemented using Python in a Jupyter Notebook environment (Google Colab).

---

## Dataset Information
The dataset used in this project is the **Online Retail II Dataset**, which contains real-world e-commerce transaction records.

The dataset includes the following attributes:
- Invoice
- StockCode
- Description
- Quantity
- InvoiceDate
- Price
- Customer ID
- Country

> **Note:** Due to file size limitations, the dataset is not uploaded to this repository.  
> The dataset exceeds GitHub’s file size limit (25 MB).  
> The dataset can be obtained from the official Online Retail II source:  
> https://archive.ics.uci.edu/ml/datasets/Online+Retail+II

---

## Methodology
The project follows the steps below:

1. Data Loading and Understanding  
2. Data Preprocessing  
   - Removal of records with missing Customer IDs  
   - Removal of returned transactions (negative quantity values)  
3. Feature Engineering  
   - Calculation of total purchase value  
4. RFM Analysis  
   - **Recency:** Number of days since the last purchase  
   - **Frequency:** Number of purchases made by the customer  
   - **Monetary:** Total amount spent by the customer  
5. Data Normalization using StandardScaler  
6. Customer Segmentation using K-Means Clustering  
7. Visualization and Interpretation of Customer Segments  

---

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## Results
Using RFM analysis and K-Means clustering, customers are segmented into three distinct groups:
- **High-value customers**
- **Medium-value customers**
- **Low-value or inactive customers**

These customer segments can be used to support personalized marketing strategies, customer retention, and data-driven business decisions.

---

## Conclusion
This project demonstrates how machine learning techniques can be applied to perform effective customer segmentation in an e-commerce environment.
The use of RFM analysis and K-Means clustering provides meaningful insights into customer purchasing behavior and helps in identifying valuable customer groups.

---

## Author
**Chotaliya Suratiben Dineshbhai**  
MCA Minor Project
