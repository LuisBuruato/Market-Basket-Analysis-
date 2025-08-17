# Market Basket Analysis – Customer Segmentation

This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis and KMeans clustering. Visualizations below help understand customer behavior across segments.

---

##  Notebooks

- **`cx_segmentation.ipynb`** – RFM segmentation, KMeans clustering, silhouette analysis, and visual exploration (2D, 3D, boxplots).
- **`customer_segmen.ipynb`** – Data preprocessing, exploratory analysis, QQ-plots, scatter and regression plots.

---

##  Visualizations

### A) Sales by Country

This bar chart shows total sales amount per country, highlighting key markets.

![Sales by Country](graficos/sales_by_country.png)

---

### B) RFM Metrics by Cluster (Boxplots)

The following boxplots show distributions of `Amount`, `Frequency`, and `Recency` across clusters. Outliers above the 95th percentile were removed for clarity.

#### Amount (Purchase Value)
| 3 Clusters | 5 Clusters | 7 Clusters |
|------------|------------|------------|
| ![Amount 3C](graficos_plotly_png/boxplot_amount_3_clusters.png) | ![Amount 5C](graficos_plotly_png/boxplot_amount_5_clusters.png) | ![Amount 7C](graficos_plotly_png/boxplot_amount_7_clusters.png) |

**Interpretation:**  
Clusters with higher medians represent customers who spend more. These groups may be prime targets for premium promotions.

#### Frequency (Purchase Frequency)
| 3 Clusters | 5 Clusters | 7 Clusters |
|------------|------------|------------|
| ![Freq 3C](graficos_plotly_png/boxplot_frequency_3_clusters.png) | ![Freq 5C](graficos_plotly_png/boxplot_frequency_5_clusters.png) | ![Freq 7C](graficos_plotly_png/boxplot_frequency_7_clusters.png) |

**Interpretation:**  
Higher medians indicate clusters of frequent buyers—valuable for loyalty campaigns.

#### Recency (Time Since Last Purchase)
| 3 Clusters | 5 Clusters | 7 Clusters |
|------------|------------|------------|
| ![Recency 3C](graficos_plotly_png/boxplot_recency_3_clusters.png) | ![Recency 5C](graficos_plotly_png/boxplot_recency_5_clusters.png) | ![Recency 7C](graficos_plotly_png/boxplot_recency_7_clusters.png) |

**Interpretation:**  
Lower recency values mean customers are recently active; high values signal textatively inactive groups—ideal re-engagement targets.

---

##  Getting Started

```bash
git clone https://github.com/LuisBuruato/Market-Basket-Analysis-.git
