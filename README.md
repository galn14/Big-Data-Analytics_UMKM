# **Big Data Analytics UMKM Customer Segmentation, Revenue Trends, and Sales Forecasting**

## **Overview**
This project is part of our coursework in the **Big Data Analytics for Business** class. The project is collaboratively 
developed by **[GalenoAreliano](https://github.com/galn14)** and [Aileen](https://github.com/aileenliexiuai). 

The goal is to apply data analytics and machine learning techniques to:
- Segment customers based on their behavior.
- Analyze revenue trends to identify business insights.
- Forecast future sales using ARIMA and LSTM models for time-series prediction.

This analysis aims to provide actionable insights for optimizing marketing strategies, improving inventory management, and enhancing customer retention.

---

## **Features**
1. **Customer Segmentation (RFM)**:
   - Segment customers into clusters such as VIPs, Dormant, etc.
   - Analyze cluster contributions to revenue and behavior patterns.

2. **Revenue Analysis**:
   - Compute total revenue and weekly trends.
   - Understand temporal revenue dynamics to identify peak periods.

3. **Product Sales Visualization**:
   - Visualize sales trends with stacked area charts.
   - Identify dominant products across time periods.

4. **Sales Forecasting**:
   - Implement **ARIMA** for traditional time-series modeling.
   - Develop an **LSTM neural network** for sequence-based sales predictions.
   - Compare ARIMA and LSTM based on their accuracy and forecast ability.

---

## **Technologies Used**
- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Data visualization.
- **Scikit-learn**: Clustering and preprocessing.
- **Statsmodels**: ARIMA modeling.
- **TensorFlow/Keras**: Building and training the LSTM model.

---

## **Dataset**
The dataset contains the following key fields:
- `Tanggal`: Transaction date.
- `Nama`: Customer name.
- `Harga`: Total transaction amount.
- `Pesanan`: Number of orders.
- **Product Columns**: Quantities of each product sold (e.g., `Ayam Cabai Hijau`, `Tuna Pedas`).

---

## **Usage**
### **1. Prerequisites**
Install the necessary libraries:
```bash
pip install pandas matplotlib scikit-learn statsmodels tensorflow
```
### **2. Run the Project**
#### 1. Load the dataset 
```
(Sorted_Order_Report_by_Date.csv).
```
#### 2. Execute the notebook to:
- Perform customer segmentation.
- Analyze revenue trends.
- Generate sales forecasts using ARIMA and LSTM.
#### 3. Interpret the results and compare forecasting models' performance.

---

## **Results and Insights**
### Customer Segmentation
- Cluster 1 (VIP Customers): High frequency, high spending, low recency. Key drivers of revenue.
- Cluster 2 (Dormant Customers): Low activity and spending. Target for reactivation campaigns.
### Revenue Trends
- Total revenue.
- Weekly trends reveal peak sales during certain weeks, allowing strategic planning.
### Sales Forecasting
- ARIMA: Traditional statistical approach with good short-term performance.
- LSTM: Deep learning approach that adapts to complex patterns, providing more robust long-term predictions.
### Model Comparison
- Accuracy: Evaluate both models using metrics like MAE, RMSE, and MAPE.
- Forecast Quality: LSTM captures non-linear patterns better, while ARIMA performs well with stationary data.

---

## **License**
This project is licensed under the MIT License. See the LICENSE file for details.
