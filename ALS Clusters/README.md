Project Title: ALS Clustering

Language: Python

Libraires used: 
Pandas
Sklearn
matplotlib

Project Description: 
The goal of this project is to remove any data that is not relevant to patient’s ALS condition. Apply a standard scalar to the data. Draw a comparison between the cluster silhouette score and number of clusters for K-means. Choose the optimal number of clusters for K-means. Fit a K-means model to the data with the optimal number of clusters chosen. Fit a PCA transformation with two features to the scaled data. Create a scatterplot of the PCA transformation data coloring each point by its cluster value.

Files Needed:
		als_data.csv
		ALS_Clustering.ipynb

How to Run:
Download the files needed, see list above, and ensure they are saved in the same directory. Open Jupyter Notebook and navigate to the directory where the files are stored. Run the notebook, no alterations to code should need to be made.

Summary: 
Analyzing the cluster distribution and characteristics observed in the scatterplot, conclusions can be draw about the ALS patient data within the relevant columns. The identified clusters may represent distinct subgroups of ALS patients based on their features, providing insights for further analysis and decision-making in patient care or research. Here there are outliers indicating there are variables that do not align with the clusters characteristics.
