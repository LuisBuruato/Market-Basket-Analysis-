# Customer Segmentation & Market Basket Analysis

This project applies **RFM analysis** and **clustering techniques** to segment customers and identify valuable insights from transaction data.  
Below are the main figures generated during the analysis.

---

## 1. Sales by Country
![Sales by Country](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/sales_by_country.png)  
*Distribution of total sales across different countries.*

---

## 2. Top 10 Customers by Amount of Events
![Top 10 Customers](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/top10_customers_amount_events.png)  
*The 10 customers with the highest transaction amounts.*

---

## 3. Top 51 Customers
![Top 51 Customers](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/top51_customers.png)  
*Highlights the top 51 customers ranked by their total purchases.*

---

## 4. Clusters Scatter
![Clusters Scatter](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos_kmeans/clusters_scatter.png)

This chart represents the **clusters generated from the market basket analysis** using clustering techniques (e.g., K-Means).

- Each **point** represents a customer or transaction in the selected feature space.  
- **Colors** indicate the **cluster each customer belongs to**, showing how they group based on similar purchasing patterns.  
- It helps identify customer segments with similar buying behaviors, which can be used to:  
  - Design **personalized marketing strategies**  
  - Optimize **product placement**  
  - Detect **frequent purchasing patterns** within each cluster  

💡 Note: The clearer and more separated the clusters are, the more distinct the buying behaviors are between segments.

## 📉 Elbow Method for Optimal Clusters

![Elbow Method](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos_kmeans/elbow_method.png)

The **Elbow Method** is a heuristic used to determine the optimal number of clusters (k) in K-Means clustering. It involves plotting the **Within-Cluster Sum of Squares (WCSS)** against the number of clusters and identifying the point where the rate of decrease sharply slows down, forming an "elbow" in the graph.

### 🔍 Interpretation

- **X-axis**: Number of clusters (k)  
- **Y-axis**: WCSS (a measure of the variance within each cluster)  

The optimal number of clusters corresponds to the point where increasing k no longer significantly reduces WCSS. This indicates that adding more clusters doesn't substantially improve the model's performance.

### ✅ Key Takeaways

- The Elbow Method provides a visual approach to selecting the number of clusters.  
- It helps identify the point where adding more clusters yields diminishing returns.  
- While useful, the method is subjective, and the "elbow" point may not always be clear.

## 📈 QQ Plot: Distribution of Purchase Amounts

![QQ Plot of Amount](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos_productos/QQ_plot_Amount.png)

This **Quantile-Quantile (QQ) plot** compares the distribution of purchase amounts against a **normal distribution**. QQ plots help assess if a dataset follows a theoretical distribution.  

### 🔍 Interpretation

- **X-axis**: Theoretical quantiles from the normal distribution  
- **Y-axis**: Observed quantiles from the purchase amounts  

In this plot, the points **deviate from the straight line**, indicating that the purchase amounts **do not follow a normal distribution**. This is common in financial data, where a few purchases are significantly larger than the majority.  

### ✅ Key Takeaways

- **Skewness**: The deviation from the straight line suggests the data may be skewed.  
- **Heavy Tails / Outliers**: Extreme values are present in the data.  
- **Impact**: Non-normal distribution may affect statistical modeling and analysis choices.  

Understanding the distribution of purchase amounts is crucial for **anomaly detection, pricing strategies, and customer segmentation** in market basket analysis.

## 📈 QQ Plot: Distribution of Purchase Frequencies

![QQ Plot of Frequency](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos_productos/QQ_plot_Frequency.png)

This **Quantile-Quantile (QQ) plot)** compares the distribution of purchase frequencies against a **normal distribution**. QQ plots help assess if a dataset follows a theoretical distribution.  

### 🔍 Interpretation

- **X-axis**: Theoretical quantiles from the normal distribution  
- **Y-axis**: Observed quantiles from the purchase frequencies  

In this plot, the points **deviate from the straight line**, indicating that the purchase frequencies **do not follow a normal distribution**. This is common in transaction data, where a few items are purchased very frequently.  

### ✅ Key Takeaways

- **Skewness**: The deviation from the straight line suggests the data may be skewed.  
- **Heavy Tails / Outliers**: Extreme values are present in the data.  
- **Impact**: Non-normal distribution may affect statistical modeling and analysis choices.  

Understanding the distribution of purchase frequencies is important for **inventory management, demand forecasting, and product bundling** in market basket analysis.


## 📈 QQ Plot: Distribution of Recency

![QQ Plot of Recency](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos_productos/QQ_plot_Recency.png)

This **Quantile-Quantile (QQ) plot)** compares the distribution of recency values against a **normal distribution**. QQ plots help assess if a dataset follows a theoretical distribution.  

### 🔍 Interpretation

- **X-axis**: Theoretical quantiles from the normal distribution  
- **Y-axis**: Observed quantiles from the recency values  

In this plot, the points **deviate from the straight line**, indicating that the recency values **do not follow a normal distribution**. This is common in customer behavior data, where a few customers made recent purchases, and many others haven't purchased in a while.  

### ✅ Key Takeaways

- **Skewness**: The deviation from the straight line suggests the data may be skewed.  
- **Heavy Tails / Outliers**: Extreme values are present in the data.  
- **Impact**: Non-normal distribution may affect statistical modeling and analysis choices.  

Understanding the distribution of recency values is important for **customer segmentation, churn prediction, and personalized marketing strategies** in market basket analysis.
If 

## 📊 Client Segmentation Distribution

![Client Segmentation Distribution](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos_productos/distribution_clients_segment.png)

This **bar chart** illustrates the distribution of customers across different segments based on their purchasing behavior.  

The segmentation is typically derived from **RFM (Recency, Frequency, Monetary)** analysis, which categorizes customers into groups such as:

- **Champions**: High recency, frequency, and monetary values  
- **Loyal Customers**: High frequency and monetary, but lower recency  
- **Potential Loyalists**: High recency, moderate frequency and monetary  
- **At Risk**: Low recency, frequency, and monetary  

This segmentation helps businesses **tailor marketing strategies, optimize product offerings, and improve customer retention** by understanding the purchasing patterns of different customer groups.

## 10. Customer Segments (Pie Chart)
![Pie Segment Clients](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/pie_segment_clients.png)

## 11. 2D Regression Plots
![2D Regression Plots](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/regplots_2D.png)

## 12. 3D Scatter Plot
![3D Scatter Plot](https://raw.githubusercontent.com/LuisBuruato/Market-Basket-Analysis-/main/graficos/scatter3D.png)


