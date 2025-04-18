# 🛍️ E-Commerce RFM Segmentation & Revenue Recovery Dashboard

An interactive Streamlit dashboard that analyzes customer behavior using RFM (Recency, Frequency, Monetary) analysis to uncover customer segments and simulate revenue recovery from at-risk users. Built using the Online Retail II dataset, this app enables data-driven decisions for improving customer retention and optimizing marketing efforts.

---

## 📌 Description

This project simulates a real-world e-commerce analytics use case, inspired by companies like **Nykaa**, **Blinkit**, and **Flipkart**. It focuses on understanding user behavior from product view to purchase and identifying **where users drop off** in the purchase funnel.

Key objectives include:

- **Segmenting customers** using RFM analysis to identify Champions, Loyal Customers, At-Risk users, etc.
- **Simulating recovery strategies** (discounts, nudges) to bring back inactive users and boost revenue.
- Providing **interactive insights** through charts, filters, and download options to support strategic decision-making.

Perfect for e-commerce businesses looking to increase **customer retention**, reduce **churn**, and **recover lost revenue**.

---

## 🚀 Live Demo

🔗 [Click here to try the live app](https://rfm-analysis-and-recovery-simulation-aj4u58p32cfnq7ajhbbhuw.streamlit.app/)  

---

## 📊 Features

- **Interactive Filters**: Country selector and date range slider  
- **RFM Segmentation**: Identify Champions, Loyal, Potential Loyalists, and At-Risk customers  
- **Visual Insights**:
  - Segment Distribution Pie Chart
  - Revenue Contribution Bar Chart
  - RFM Heatmap
- **Revenue Recovery Simulation**: Adjustable slider to simulate potential recovery  
- **Data Export**: Downloadable CSV of segmented customers  

---

## 🧠 Technologies Used

- `Python`
- `Pandas`, `NumPy`
- `Plotly` for interactive visualizations
- `Streamlit` for dashboard and deployment

---

## 📁 Dataset

**Dataset Used**: [Online Retail II Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)  
- ~500K rows of transactional data from a UK-based online retailer  
- Fields include: `Invoice`, `InvoiceDate`, `Customer ID`, `Country`, `Product Code`, `Quantity`, `UnitPrice`

---

## 🛠️ How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/ecommerce-rfm-dashboard.git
   cd ecommerce-rfm-dashboard

2. **Install Dependencies**
      ```bash
   pip install -r requirements.txt
      
4. **Run Streamlit App**
 ```bash
    streamlit run app.py



  

