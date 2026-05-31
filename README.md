```markdown
# Customer Segmentation Analytics using CRISP-DM, K-Means and SAS

## Project Overview

This project presents a customer segmentation and decision-support analysis developed as part of my M.Sc. in Informatics. The project applies the **CRISP-DM framework** to analyze customer purchasing behaviour and identify meaningful customer groups using unsupervised learning.

The analysis was based on a retail dataset of approximately **3,900 customers**, using behavioural, demographic, purchasing, and satisfaction-related variables. The main goal was to transform raw customer data into interpretable customer segments that can support customer relationship management, marketing planning, KPI design, and business decision-making.


---

## Research and Business Context

Retail organizations often collect large volumes of customer data, but without segmentation it can be difficult to understand how different customer groups behave, spend, and respond to products or services.

This project addressed that challenge by using clustering techniques to identify groups of customers with similar behavioural patterns. The output was not only a statistical model, but also a practical segmentation framework that can support:

- CRM targeting
- Customer retention strategies
- Marketing campaign design
- KPI monitoring
- A/B testing ideas
- Customer value analysis
- Evidence-based business planning

---

## Methodology

The project followed the **CRISP-DM** methodology:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modelling
5. Evaluation
6. Deployment Recommendations

The modelling stage focused on unsupervised learning, especially **K-means clustering**, supported by hierarchical validation and internal cluster validation metrics.

---

## Data Preparation

The dataset included customer-level variables related to:

- Frequency of purchases
- Previous purchases
- Purchase amount
- Review rating
- Age
- Payment method
- Subscription status
- Product category
- Location
- Season
- Shipping type
- Promotional code usage

Data preparation included:

- Variable cataloguing
- Role and measurement definition
- Data cleaning and validation
- Handling implausible values
- Preparing behavioural and demographic variables
- Standardizing variables for clustering
- Reviewing expected ranges and measurement levels

![Variable Catalogue](Variable%20catalogue%20with%20role%20and%20measurement.png)

---

## Clustering Approach

The analysis evaluated multiple clustering scenarios using different numbers of clusters.

The final model selected a **four-cluster K-means solution**, based on a combination of:

- Internal validation metrics
- Cluster size balance
- Interpretability
- Hierarchical cross-checking
- Business usefulness of the resulting segments

The four-cluster solution was selected because it provided a clear and interpretable structure while maintaining good internal validity.

---

## Cluster Validation

Several diagnostic indicators were used to compare candidate cluster solutions, including:

- Pseudo F Statistic
- Approximate Expected Overall R-Squared
- Cubic Clustering Criterion (CCC)
- RMSSTD
- Minimum inter-centroid distance
- Maximum RMSSTD
- Cluster size distribution

The evaluation compared solutions with 2, 3, 4, and 5 clusters. The four-cluster solution provided a balanced and interpretable segmentation structure.

![Cluster Diagnostics](summarizes%20diagnostics%20across%20K.png)

---

## Hierarchical Cross-Checking

Ward’s hierarchical clustering method was used as an additional validation step to compare the structure of the K-means solution.

The dendrogram helped confirm that the customer data contained meaningful grouping patterns and supported the final selection of a four-segment solution.

![Ward Hierarchical Validation](Ward%20hierarchical%20validation.png)

---

## Cluster Profiles

The final segmentation identified four customer groups with distinct characteristics in terms of spending, purchasing behaviour, age distribution, and satisfaction patterns.

The profiling stage examined cluster-level means, standard deviations, minimums, maximums, medians, and distribution characteristics for key variables such as:

- Review rating
- Age
- Previous purchases
- Purchase amount

![Cluster Means](Cluster%20means%20and%20standard%20deviations%20on%20original%20scales.png)

---

## Statistical Testing

To validate differences between the identified segments, statistical tests were applied, including:

- ANOVA
- Kruskal-Wallis test

These tests helped confirm that the clusters showed statistically meaningful differences across behavioural indicators.

---

## Key Findings

The analysis showed that:

- Customers can be separated into four distinct behavioural segments.
- The segments differ in spending patterns, purchase frequency, age distribution, and satisfaction levels.
- Younger and older customers demonstrate different spending and satisfaction behaviours.
- Premium customers spend more and show stronger loyalty patterns.
- Some older customer groups showed reduced spending and lower satisfaction.
- The four-segment solution was easier to interpret and more practical for business use than more complex alternatives.

---

## Business Recommendations

The segmentation results were translated into practical business recommendations, including:

- Develop segment-specific marketing plans.
- Use personalized CRM communication based on behavioural patterns.
- Design retention strategies for high-value and loyal customers.
- Monitor satisfaction changes by segment.
- Test targeted campaigns using A/B testing.
- Build dashboards to track segment performance over time.
- Refresh the segmentation model periodically as customer behaviour changes.

---

## Governance and Deployment Considerations

The project also considered practical and governance-related aspects of using customer segmentation in an operational environment.

These included:

- Data minimization
- Privacy-aware use of behavioural data
- Transparent segment rules
- Avoiding over-personalization
- Monitoring model performance
- Reviewing segment stability over time
- Building KPI dashboards for business users
- Creating clear documentation for repeatable analysis

---

## Tools and Techniques Used

- SAS Studio
- CRISP-DM framework
- K-means clustering
- Ward hierarchical clustering
- Internal validation metrics
- ANOVA
- Kruskal-Wallis test
- Descriptive statistics
- Customer segmentation
- Data preparation and validation
- Decision-support modelling
- CRM-oriented analysis

---

## Skills Demonstrated

This project demonstrates skills in:

- Data Analysis
- Customer Segmentation
- Unsupervised Machine Learning
- Statistical Analysis
- SAS Analytics
- Business Intelligence Thinking
- Model Evaluation
- Research Design
- Data Preparation
- CRM Analytics
- Decision Support
- KPI Design
- Governance-Aware Analytics
- Business-Oriented Interpretation

---

## Author

**Diaa Abu Arar**  
M.Sc. Informatics | IT, Data & Operations Analytics  
LinkedIn: [linkedin.com/in/diaa-abu-arar](https://www.linkedin.com/in/diaa-abu-arar)
```
