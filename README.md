# Customer-Segmentation
Data Loading and Exploration:

Loaded customer segmentation data from a CSV file using pandas (pd.read_csv).
Used df.info() to get an overview of the dataset, including data types and missing values.
Visualized categorical data distribution with a count plot (sns.countplot for gender and a pie chart for preferred category).
Data Visualization:

Plotted a line plot (sns.lineplot) to analyze the relationship between income and spending score.
Created an age group feature (df['age_group']) by binning ages into groups and visualized its distribution using a pie chart.
Data Preprocessing:

Encoded categorical variables using LabelEncoder from sklearn.preprocessing.
Correlation Analysis:

Calculated the correlation matrix (corr_df) for numerical features and visualized it using a heatmap (sns.heatmap).
Clustering Analysis (K-Means):

Selected numerical features (float64, int64) for clustering.
Applied StandardScaler from sklearn.preprocessing to standardize numerical features.
Used the Elbow method to determine the optimal number of clusters (plt.plot of Within-Cluster Sum of Squares (WCSS) against number of clusters).
Implemented K-Means clustering (KMeans from sklearn.cluster) on sample data (X) and visualized the clusters (plt.scatter).
