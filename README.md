# Customer Segmentation & Market Basket Analysis

This project explores customer segmentation and market basket analysis by using transaction data.  
We apply RFM (Recency, Frequency, Monetary) analysis, clustering, and visualization to better understand customer behavior and product sales.

---

## 📊 Data Visualizations

### 1. Sales by Country
![Sales by Country](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/sales_by_country.png)  
Shows the distribution of sales across different countries, highlighting the top contributors to revenue.

---

### 2. Top 10 Customers by Transaction Amount
![Top 10 Customers](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/top10_customers_amount_events.png)  
The customers with the highest transaction amounts, useful for identifying VIP clients.

---

### 3. Top 51 Customers
![Top 51 Customers](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/top51_customers.png)  
Expanded view of the most valuable customers.

---

### 4. Clusters Scatter Plot
![Clusters Scatter](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/clusters_scatter.png)  
Visual representation of customer clusters based on RFM metrics.

---

### 5. Elbow Method
![Elbow Method](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/elbow_method.png)  
Used to determine the optimal number of clusters (K) for segmentation.

---

### 6. QQ Plots (RFM Variables)
- **Amount**  
![QQ Plot Amount](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/QQ_plot_Amount.png)  
- **Frequency**  
![QQ Plot Frequency](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/QQ_plot_Frequency.png)  
- **Recency**  
![QQ Plot Recency](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/QQ_plot_Recency.png)  

These QQ plots test the normality of RFM variables.

---

### 7. Client Segment Distribution
![Distribution Clients Segment](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/distribution_clients_segment.png)  
Shows how customers are distributed across different segments.

---

### 8. Pie Chart of Client Segments
![Pie Segment Clients](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/pie_segment_clients.png)  
Proportional representation of customer segments.

---

### 9. Regression Plots (2D)
![Regression Plots](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/regplots_2D.png)  
Examines the relationship between RFM variables.

---

### 10. 3D Scatter of Clusters
![3D Scatter](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/scatter3D.png)  
A 3D visualization of the clusters across Recency, Frequency, and Monetary value.

---

### 11. Top Products by Events and Amount
- **Top 10 Products by Amount of Events**  
![Top 10 Products Events](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/top10_products_amount_events.png)  

- **Top 50 Products by Events**  
![Top 50 Products Events](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/top50_products_events.png)  

- **Top 15 Products by Amount**  
![Top 15 Products Amount](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/top_15_products_amount.png)  

- **Top 50 Products by Amount**  
![Top 50 Products Amount](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/top_50_products_amount.png)  

---

### 12. Silhouette Scores for Clustering
- **3 Clusters**  
![Silhouette 3](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/silhouette_3_clusters.png)  

- **5 Clusters**  
![Silhouette 5](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/silhouette_5_clusters.png)  

- **7 Clusters**  
![Silhouette 7](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/silhouette_7_clusters.png)  

Helps evaluate the quality of clustering and select the best number of clusters.

---

## 🚀 Conclusion
- The analysis reveals valuable customer segments and purchasing behavior.  
- Top customers and products can be targeted with personalized marketing.  
- Clustering models provide insights into how to group and manage different types of clients.  

---

## 📂 Project Structure
.
├── cx_segmentation.ipynb # Jupyter Notebook with full analysis
├── graficos/ # Folder containing all plots (PNGs)
└── README.md # Documentation with visual results
