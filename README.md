# Pokemon Clustering Models
This Jupyter notebook uses clustering models to analyze and visualize data for a Pokemon dataset. The following packages were used:

numpy
pandas
matplotlib.pyplot
seaborn
mpl_toolkits.mplot3d
scipy.cluster.hierarchy
sklearn.preprocessing.MinMaxScaler
sklearn.decomposition.PCA
sklearn.cluster.AgglomerativeClustering
The data used is from the "Pokemon.csv" file. The notebook begins with exploratory data analysis and data visualization to gain insights into the dataset. Then, hierarchical clustering and principal component analysis (PCA) are performed to group similar Pokemons together. Finally, Agglomerative Clustering is used to create clusters and the results are visualized using a pair plot.

## Exploratory Data Analysis and Visualization
The pokemon dataframe is loaded from the "Pokemon.csv" file and displayed using the head() method. The info() and describe() methods are also used to get information about the dataset.

Several visualization techniques are used to better understand the data. These include bar charts, countplots, distplots, jointplots, boxplots, and heatmaps. These plots are used to visualize the counts of different types of Pokemons, the distribution of the total attribute, the correlation between different attributes, and the distribution of the HP attribute.

## Hierarchical Clustering and PCA
The scipy.cluster.hierarchy package is used to create a dendrogram to visualize the hierarchical clustering of the Pokemons. The dendrogram is created using the Euclidean distances between the Pokemons.

The sklearn.preprocessing.MinMaxScaler package is used to scale the data before performing PCA. PCA is then performed to reduce the dimensionality of the data to three principal components. A 3D scatter plot is used to visualize the Pokemons using the principal components.

## Agglomerative Clustering
The sklearn.cluster.AgglomerativeClustering package is used to create clusters of the Pokemons. The number of clusters is set to three and the affinity is set to Euclidean. The results are visualized using a pair plot.
