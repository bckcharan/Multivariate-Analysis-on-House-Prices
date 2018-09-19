# Multivariate-Analysis-on-House-Prices

GOAL
----
1. To explore the concepts of Multivariate Analysis
2. Dimension Reduction on large dataset
3. Predict House Prices

Tasks
-----
1. Fetch Data
2. Data Pre-processing (Missing Values, Correlation Analysis, Outlier Analysis)
3. Exploratory Analysis (Insights, Visualizations)
4. Principal Component Analysis
5. Cluster Analysis
6. Factor Analysis
7. Build prediction models
8. Evaluate model performance

Key Observations
----------------
1. Excluded observations having Mahlanobis distance greater than 16.
2. Reduced features to 3 principal components - PC1(Overall), PC2(Second Floor), PC3(Basement)
3. Reduced observations to 5 critical clusters
4. Used linear regression modeling to build prediction model for house price

Results
-------
1. Reducing dimensions to 3 principal components captures 75% variance in dataset.
2. Formed 5 groups of houses using cluster analysis, each representing unique combination of features
3. Building models on Principal components reduced model complexity and achieved almost same accuracy as on complete feature set.
