# Customer Segmentation using RFM & K-Means

## Overview

Customer segmentation helps businesses understand different groups of customers and target them effectively.
This project focuses on segmenting customers based on their purchasing behavior using **RFM (Recency, Frequency, Monetary)** analysis and **K-Means clustering**.

---

## Objective

The main goals of this project are:

* Identify high-value customers
* Segment customers into meaningful groups
* Help businesses improve marketing strategies and customer retention

---

## Dataset

* Dataset: Online Retail Dataset
* Contains transaction-level data including customer ID, invoice date, quantity, and price

---

## Tools & Technologies Used

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Techniques:**

  * Data Cleaning & Preprocessing
  * RFM Feature Creation
  * Clustering (K-Means)
  * Data Visualization

---

## Data Preprocessing

* Removed missing values and duplicates
* Filtered out negative or invalid transactions
* Converted date columns to proper datetime format

---

## RFM Analysis

* **Recency (R):** How recently a customer made a purchase
* **Frequency (F):** How often a customer purchases
* **Monetary (M):** Total amount spent by the customer

These metrics were used to understand customer behavior.

---

## Clustering (K-Means)

* Applied K-Means clustering on RFM features
* Used **Elbow Method** to determine optimal number of clusters
* Segmented customers into distinct groups

---

## Customer Segments

* New Customers → Have good recency.
* Lost Customers →  Have high recency and low frequency
* Loyal Customers → Frequent buyers with high spending
* At-Risk Customers → Haven’t purchased recently

---

## Business Recommendations
- New Customers → Provide onboarding offers or welcome discounts  
- Lost Customers → Send personalized messages to understand why they left
- Loyal Customers → Loyalty programs, exclusive offers, early access
- At-Risk Customers → Re-engagement campaigns, discounts 


## Key Insights

* A small group of customers contributes to a large portion of revenue
* High-value customers should be targeted with loyalty programs
* At-risk customers need re-engagement strategies
* Marketing campaigns can be personalized based on segments

---

## Conclusion

This project demonstrates how businesses can use segmentation to:

* Improve customer targeting
* Increase revenue through personalized marketing
* Enhance customer retention strategies

---

## Future Improvements

* Use advanced clustering techniques (DBSCAN, Hierarchical)
* Deploy as an interactive dashboard

---

