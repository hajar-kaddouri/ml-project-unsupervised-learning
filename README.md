# machine_learning_project-unsupervised-learning
## Structure
- Introduction
- EDA
- Preprocessing
- hierarchical clustering,
- Conclusion

## Introduction
- The aim of the study : is to understand the patterns of a wholesale store by implementing Preprocessing,the clustering methods and PCA.
### Duration:
Approximately 1 hour and 40 minutes
### Project Description:
Data Understanding and Preprocessing: The dataset includes features 'Fresh', 'Milk', 'Grocery', 'Frozen', 'Detergents_Paper', and 'Delicatessen', 'channel, 'region' was thoroughly cleaned, missing values were handled, outliers were treated, and normalization was performed using the standard scaler.

K-means Clustering Application: The elbow method was employed to ascertain the optimal number of clusters, leading to the formation of three main clusters. These clusters segregated customers based on their purchasing behavior for different products.

Insights from K-means: Identified three distinct customer groupings, including one that purchases more 'Fresh' and 'Frozen' products (likely restaurants or cafes), another that purchases more 'Grocery', 'Milk', and 'Detergents_Paper' (likely grocery stores or supermarkets), and a third group with a balanced mix of all product categories. Noted some co-purchasing trends, particularly 'Fresh' with 'Frozen', and 'Grocery' with 'Milk' and 'Detergents_Paper'.

Hierarchical Clustering Application: Performed hierarchical clustering to visualize the hierarchical structure of the data. The dendrogram suggested 6 detailed clusters at a lower level and 2 broader categories at a higher level, when cut at a distance of 10 with 3 diffrent color.

Principal Component Analysis (PCA) Deployment: PCA was performed for dimensionality reduction, which indicated that 'Detergents_Paper', 'Grocery', and 'Milk' are the most influential variables in the first principal component, and 'Fresh', 'Frozen', and 'Delicatessen' in the second. These two principal components together explained approximately 72% of the total variance in the data.

Conclusive Business Insights: Insights were drawn from both clustering methods and PCA, which can help understand customer segmentation and purchase patterns better. The relationships among different product categories and the identified customer types can serve as a foundation for devising personalized marketing strategies, targeted promotional offers, and optimizing the supply chain management.

