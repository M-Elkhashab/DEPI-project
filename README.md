
Vendor Performance and Material Defect Analysis Report:

1. Executive Summary

Goals:
The project’s main goal is to evaluate vendor and material quality based on defect counts, downtime, and management. By analyzing supplier performance and defect occurrences, the aim is to provide actionable insights to enhance the supply chain, reduce defects, and improve overall vendor management.

Key Findings:
- Vendor Performance: Certain vendors, such as O-ace and Donware, have significantly higher downtime, impacting production and efficiency. Vendor 2 (Plustax) and Vendor 59 (Zuntexon) have notably poor performance regarding defect counts.
- Defect Types: Frequent defects include Bad Seams and Weak Walls, which require rework or product rejection, leading to cost increases.
- Material Impact: Materials such as Mechanical Parts, Hardware, Corrugate, and Batteries exhibit the highest defect rates, with Pumps being the worst managed material by defect count.

Recommendations:
- Vendor Improvement: Prioritize corrective actions for Plustax and Zuntexon to address consistent quality issues. Conduct performance reviews for vendors with high defect counts and downtime.
- Material-Specific Measures: Implement stricter quality control on high-risk materials like Mechanical Parts and Batteries to reduce defects and downtime.
- Operational Focus: Investigate inefficiencies at plants with high defects and downtime, especially those utilizing Mechanical Parts and Hardware.



 2. Introduction

Project Purpose:
The purpose of this analysis is to evaluate the quality performance of various vendors based on defect occurrences and their impact on downtime and production delays. The findings will help identify key areas for improvement in vendor management and material handling.

Problem Statement:
The project aims to answer the following critical questions:
1. Who are the worst-performing suppliers based on defect counts and downtime?
2. Which materials exhibit the highest defect rates, and how does this impact operational efficiency?
3. Is there a correlation between defects and downtime across suppliers?

Data Sources and Methods:
Data was collected from various sources, including supplier defect logs, downtime reports, and material performance metrics. The analysis was conducted using descriptive statistics, bar charts, scatter plots, and correlation matrices to visualize key trends.

---

 3. Data Exploration

Data Overview:
- Size and Format: The dataset includes detailed information about defects, vendor performance, material types, and downtime.
- Data Cleaning: Steps taken include:
- Removal of duplicate records in defect columns.
- Reassignment of IDs for duplicate items.
- Imputation of missing downtime values using the mode.
- Formatting corrections in date columns.

Descriptive Statistics and Visualizations:
- Defect Distribution: A histogram showing defect counts per vendor and material type was created to explore the variation in quality.
- Downtime Analysis: A bar chart ranks the top 10 vendors by downtime, highlighting those with operational inefficiencies.
- Correlation Matrices: These matrices identified any relationships between defect counts and downtime, revealing that while some vendors show high downtime with high defect counts, others do not.

---

 4. Data Analysis

Key Findings:
1. Worst Suppliers by Downtime: 
 - O-ace (720 units) and Donware (375 units) have the highest average downtime, severely affecting production.
 - Other vendors such as White-high and Citydexon also show high downtimes.

2. Defects by Category: 
 - Bad Seams and Weak Walls are the most common defects.
 - These defects contribute to rework and product rejection, escalating costs.

3. Supplier Defects by Type: 
 - Hotity has the highest average defect quantity at 204.8K, followed by Plextechi and O-ace.

4. Defect Trends by Month/Year:
 - Analysis of monthly defect rates reveals higher occurrences in certain months, indicating possible seasonal or operational factors.

5. Worst Managed Materials:
 - Mechanical Parts and Hardware are among the worst-managed materials, showing the highest defect counts and downtime.

Unexpected Discoveries:
 - While there is a general trend of increased downtime leading to higher defects, certain suppliers break this pattern, indicating that other operational factors may be at play.

---

 5. Insights and Recommendations

Vendor-Specific Actions:
 - Vendor Benchmarking: Prioritize vendors with the highest defect rates for performance improvement plans, focusing on Vendor 2 (Plustax) and Vendor 59 (Zuntexon).
 - Supplier Audits: Conduct audits for high-downtime vendors like O-ace and Donware to identify inefficiencies and root causes.

Material Management:
 - Improved Controls: Implement stronger quality controls for materials such as Corrugate and Batteries to reduce defect rates.
 - Inventory and Handling: Review storage and handling procedures for materials with frequent defects, such as Mechanical Parts and Hardware.

Operational Efficiency:
 - Downtime Reduction: Address downtime by focusing on operational bottlenecks in plants that frequently handle defective materials.

Further Analysis:
 - Root Cause Analysis: Dive deeper into the causes of high defects and downtime for specific materials and vendors.
 - Predictive Modeling: Consider developing predictive models to anticipate future defect trends.

---

 6. Limitations and Future Work

Limitations:
 - Missing Data: Some downtime values were missing, which may have affected the accuracy of certain analyses.
 - Non-Linear Correlations: While trends were identified, further analysis is required to fully understand the relationship between downtime and defect rates.

Future Work:
 - Further Audits: Conduct root cause analyses for vendors and materials exhibiting extreme performance outliers.
 - Predictive Analytics: Develop models to forecast defect occurrences and downtime based on current trends.

---

 7. Conclusion

Summary of Findings:
- The top suppliers contributing to defects and downtime are O-ace, Donware, and Plustax, all of which need corrective actions.
- Materials such as Mechanical Parts and Batteries are associated with the highest defect rates, requiring stricter controls.

Impact:
By taking actionable steps to address these issues, the organization can improve operational efficiency, reduce costs, and enhance overall product quality and vendor performance.

---

 8. Dashboard Interactivity

Features:
 - User Interactivity: Users can filter data by vendor, defect type, and material category, allowing for a customized view of the data.
 - Visual Elements:
 1. Top 10 Worst Suppliers by Downtime: A bar chart shows the vendors with the most downtime.
 2. Defect Quantity by Category: A pie chart displays the breakdown of defect types.
 3. Supplier Defects by Type: Line charts and scatter plots provide insights into vendor performance.
 4. Defects Per Month & Year: A time series analysis reveals defect trends over time.
 5. Worst Managed Materials: A bar chart shows the materials most affected by defects and downtime.
 - Annotations and Highlights: Key insights and critical trends are highlighted in the dashboard to guide decision-making.
