# machine_learning_project-unsupervised-learning


### Project/Goals
The goal of this project is to perform a full unsupervised learning machine learning analysis on the "Wholesale Data" dataset. This dataset contains information about clients of a wholesale distributor, including their annual spending on various product categories. The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked.


### Process

1. **Data Import and Cleaning**: The dataset was imported into Python, and initial checks were performed to identify any missing or incorrect data. Data cleaning techniques were applied to handle any discrepancies in the dataset.

2. **EDA and Visualization**: Various visualizations such as histograms, box plots, scatter plots, and heatmaps were created to explore the relationships and trends between different variables in the dataset. Correlation analysis was conducted to identify significant correlations between product categories.

3. **Outlier Detection and Treatment**: Outliers in the dataset were detected using visualization techniques and treated using appropriate methods such as winsorization.

4. **Data Transformation and Feature Selection**: The data was transformed by standardizing and normalizing the variables to make them comparable across different scales. Feature selection techniques such as PCA and random forest regression were employed to identify the most important features contributing to the overall variance in the dataset.

5. **Clustering Analysis**: Both KMeans clustering and hierarchical clustering algorithms were implemented to segment customers based on their purchasing behavior. The optimal number of clusters was determined using techniques such as the silhouette score and dendrogram visualization.

6. **Interpretation and Visualization of Results**: The results of clustering analysis were interpreted and visualized to understand distinct customer segments and their characteristics.

### Results

- **Distinct Customer Segments**: Three distinct customer segments were identified based on their spending patterns, indicating different types of businesses or consumer behaviors.
  
- **Feature Importance**: 'Fresh', 'Milk', and 'Grocery' were identified as the most important features in predicting customer segments, while PCA revealed four principal components explaining approximately 94% of the total variance in the dataset.

- **Correlation Matrix and Pattern**: Moderate to strong correlations were observed between certain product categories, providing insights into customer purchasing behavior and potential cross-selling strategies.

- **Cluster Characteristics**: Each cluster exhibited distinct purchasing behaviors, with differences in spending patterns across different product categories.

### Challenges and Future Goals

- **Data Quality**: Handling missing or incorrect data was a challenge during the data cleaning process. In the future, implementing more robust data cleaning techniques could improve data quality.
  
- **Model Interpretability**: Interpreting the results of clustering analysis and translating them into actionable insights for business decisions can be challenging. Further exploration of clustering techniques and visualization methods could enhance model interpretability.

- **Personalization**: Incorporating additional customer information such as demographics or purchase history could enhance the segmentation analysis and enable personalized marketing strategies in the future.

Overall, the project provides valuable insights into customer segmentation and purchasing behavior, laying the groundwork for further analysis and decision-making in marketing and business strategy.

