# ODI-Batting-KMeans-Clustering
Clustering ODI cricket players based on batting performance using K-Means algorithm

Author
Kritika Kamboj

#Executive Summary
This project employs the K-Means clustering algorithm to segment One Day International (ODI) cricket players based on their career statistics. The objective is to identify and analyze distinct player archetypes, such as batsmen, bowlers, and all-rounders, by grouping individuals with similar performance metrics. The insights derived from this analysis can be valuable for talent scouting, team formation, and strategic performance evaluation.

#Dataset
The analysis is performed on a dataset containing comprehensive career statistics for ODI cricket players. This dataset includes key performance indicators such as runs scored, wickets taken, highest score, and batting and bowling averages.

Data Source: [Please insert the specific URL or source of the dataset here]

#Methodology
The project follows a rigorous data science pipeline to ensure the robustness and accuracy of the results:

#Data Acquisition and Initial Assessment: The raw data is loaded and a preliminary assessment is conducted to understand its structure, identify data types, and check for missing or duplicate values.

#Data Preprocessing and Feature Engineering: The dataset is cleaned by handling inconsistent data formats, such as special characters in the 'Highest Score' column, and converting columns to appropriate numerical types. String-based columns, like 'Span', are parsed to extract relevant numerical features (e.g., career duration).

#Exploratory Data Analysis (EDA): Statistical summaries and visualizations are used to explore the distribution of key variables and identify potential relationships.

#K-Means Clustering: The preprocessed data is used as input for the K-Means algorithm to partition players into a predetermined number of clusters.

#Cluster Interpretation: The characteristics of each resulting cluster are analyzed to define and label the player segments (e.g., 'Power Hitters,' 'Strike Bowlers,' 'Defensive Batsmen').

#Files
kmeans_project (2).ipynb: A Jupyter Notebook containing the complete source code, detailed analysis, and visualizations.

#Technologies and Libraries
-Programming Language: Python

-Core Libraries: pandas, numpy, scikit-learn

-Visualization: matplotlib, seaborn, plotly.express







