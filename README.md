# SpendingDataVisaSMi
 
# Spending Analysis Project

## Objective
The Spending Analysis Project aims to analyze quarterly relationships between economic indicators, such as **Consumer Price Index (CPI)** and **Spending Momentum Index (SMI)**, and **e-commerce spending**. By leveraging unsupervised learning techniques, we uncover meaningful clusters, identify outliers, and provide actionable insights for stakeholders.

## Key Findings
1. **K-Means Clustering**:
   - Optimal number of clusters: **5**.
   - Silhouette Score: **0.63**, indicating good cluster separation.
   - Strengths: Captures distinct groupings of data points but forces all points into clusters.

2. **DBSCAN Clustering**:
   - Optimal Parameters: `eps=1.5`, `min_samples=5`.
   - Silhouette Score: **0.63**, slightly outperforming K-Means.
   - Strengths: Identifies outliers and preserves data integrity by not forcing all points into clusters.

3. **Cluster Insights**:
   - **Cluster 0 (Majority Behavior)**: Represents typical quarters with moderate CPI, SMI, and e-commerce spending.
   - **Cluster -1 (Outliers)**: Captures quarters with significantly low CPI, SMI, and spending, such as **Q2 2020** and **Q3 2020**, likely influenced by the COVID-19 pandemic.

## Recommendations
1. **Analyze Outliers**:
   - Investigate economic events like policy changes, stimulus efforts, or global crises affecting outlier quarters.

2. **Enhance Data**:
   - Incorporate additional features, such as employment rates, wage growth, and consumer confidence indices.

3. **Improve Modeling**:
   - Explore time-series models (e.g., ARIMA, LSTM) to predict future spending trends.
   - Experiment with advanced clustering techniques, such as Gaussian Mixture Models or Hierarchical Clustering.

4. **Actionable Business Strategies**:
   - Focus on marketing campaigns during low-SMI periods to encourage spending.
   - Adjust product offerings during economic downturns to focus on essentials.

## Files in This Repository
- **Spending_Analysis_Report.ipynb**: Jupyter Notebook containing the code, analysis, and visualizations.
- **Spending_Analysis_Report.pdf**: Comprehensive PDF report summarizing findings and recommendations.
- **Aligned_Dataset_for_Analysis.csv**: Dataset used for analysis, including normalized features and cluster labels.

## How to Use
1. Open the `Ecommerce_SMI_Analysis.ipynb` file in Jupyter Notebook to explore the code and visualizations.
2. Review the `Spending_Analysis_Report.pdf` for a detailed summary of the findings.
3. Use the `Aligned_Dataset_for_Analysis.csv`, `ecommerce_customer_data_large.csv`, `filtered_smi_data.csv` to conduct further analysis or replicate the results.


## Next Steps
- Extend the dataset with additional features for a more comprehensive analysis.
- Create a proper power point to present dats for majority investors.
- Implement alternative modeling techniques to refine cluster identification.
- Share findings with stakeholders to guide business decisions.

---
**Author**: Juaniza Harris  
**Date**: December 2024  

