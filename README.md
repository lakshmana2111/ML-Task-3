# Customer Segmentation using RFM and K-Means

## 📌 Project Overview

This project performs **customer segmentation** using machine learning techniques.

Customers are grouped based on their purchasing behavior using **RFM Analysis**:

* **Recency** – How recently a customer made a purchase.
* **Frequency** – How often a customer makes purchases.
* **Monetary** – How much money a customer spends.

After calculating the RFM values, **K-Means Clustering** is used to divide customers into different groups.

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab
* Excel Dataset

---

## 📊 Project Steps

1. Load the sales dataset.
2. Check for missing values.
3. Clean the dataset by removing:

   * Missing Customer IDs
   * Cancelled invoices
   * Invalid quantities and prices
   * Duplicate records
4. Calculate the total amount for each transaction.
5. Create RFM values for each customer.
6. Standardize the RFM values using `StandardScaler`.
7. Use the **Elbow Method** to select the optimal number of clusters.
8. Apply **K-Means Clustering**.
9. Calculate the **Silhouette Score**.
10. Calculate the **Davies-Bouldin Index**.
11. Visualize the customer clusters.
12. Display the average RFM values for each cluster.

---

## 📁 Dataset

The project uses a sales dataset containing transaction information such as:

* Invoice
* Invoice Date
* Customer ID
* Quantity
* Price

---

## 📈 Machine Learning Algorithm

### K-Means Clustering

K-Means is an **unsupervised machine learning algorithm** used to divide data into groups called **clusters**.

In this project, the algorithm groups customers based on their **Recency, Frequency, and Monetary (RFM)** values.

---

## 📏 Evaluation Metrics

Two clustering evaluation metrics are used to evaluate the performance of the model.

### Silhouette Score

The **Silhouette Score** measures how well customers are separated into different clusters.

A higher Silhouette Score generally indicates better-defined clusters.

### Davies-Bouldin Index

The **Davies-Bouldin Index** measures the similarity between different clusters.

A lower value generally indicates better-separated clusters.

---

## 📌 Result

The project successfully groups customers based on their purchasing behavior using **RFM Analysis** and **K-Means Clustering**.

The resulting clusters help in understanding different types of customers and their purchasing patterns.

---

## 🚀 How to Run

1. Open the notebook in **Jupyter Notebook** or **Google Colab**.
2. Upload the `sales2.xlsx` dataset.
3. Run the notebook cells in order.
4. View the clustering results and visualizations.
