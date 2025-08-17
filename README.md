# Market Basket Analysis – Customer Segmentation

This project analyzes customer purchasing patterns and segments customers based on their buying behavior using clustering techniques. The visualizations (boxplots) display how `Amount`, `Frequency`, and `Recency` vary across clusters.

---

## 1. Introduction

- **Objective:** Segment customers based on their purchasing behavior to identify groups with similar patterns.  
- **Dataset:** Customer transaction data including products, purchase amount, and purchase frequency.  
- **Methodology:**  
  1. Data preprocessing and selection of main features (`Amount`, `Frequency`, `Recency`).  
  2. Clustering using **KMeans**.  
  3. Evaluation of clustering performance with **Silhouette Score**.  
  4. Visualization of differences across clusters using **boxplots**.

---

## 2. Boxplots per Cluster

The following boxplots illustrate the distribution of each variable across **3, 5, and 7 clusters**. Outliers were removed for clarity, and only the top variables are shown.

---

### 2.1 Amount (Purchase Value)

**3 Clusters:**

![Boxplot Amount 3 Clusters](graficos_plotly_png/boxplot_amount_3_clusters.png)

**5 Clusters:**

![Boxplot Amount 5 Clusters](graficos_plotly_png/boxplot_amount_5_clusters.png)

**7 Clusters:**

![Boxplot Amount 7 Clusters](graficos_plotly_png/boxplot_amount_7_clusters.png)

**Explanation:**  
- Clusters with a higher median represent customers who typically spend more.  
- Outliers show customers with unusually high spending behavior.  

---

### 2.2 Frequency (Purchase Frequency)

**3 Clusters:**

![Boxplot Frequency 3 Clusters](graficos_plotly_png/boxplot_frequency_3_clusters.png)

**5 Clusters:**

![Boxplot Frequency 5 Clusters](graficos_plotly_png/boxplot_frequency_5_clusters.png)

**7 Clusters:**

![Boxplot Frequency 7 Clusters](graficos_plotly_png/boxplot_frequency_7_clusters.png)

**Explanation:**  
- The median indicates the typical purchase frequency within each cluster.  
- Clusters with higher values represent more loyal or frequent buyers.  

---

### 2.3 Recency (Time Since Last Purchase)

**3 Clusters:**

![Boxplot Recency 3 Clusters](graficos_plotly_png/boxplot_recency_3_clusters.png)

**5 Clusters:**

![Boxplot Recency 5 Clusters](graficos_plotly_png/boxplot_recency_5_clusters.png)

**7 Clusters:**

![Boxplot Recency 7 Clusters](graficos_plotly_png/boxplot_recency_7_clusters.png)

**Explanation:**  
- Lower recency means customers purchased recently.  
- Higher recency means customers have not purchased in a long time (inactive customers).  

---

## 3. Conclusion

- The segmentation highlights **distinct customer groups** based on purchase amount, frequency, and recency.  
- **High-value clusters** identify premium customers worth targeting for loyalty campaigns.  
- **High-frequency clusters** represent engaged, repeat customers.  
- **High-recency clusters** reveal inactive customers who may need reactivation strategies.  

---

📊 With this segmentation, businesses can design **targeted marketing strategies** for each customer group.
