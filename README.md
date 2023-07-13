# Insurance Market Segmentation

The goal of this case is to create a customer segmentation to help target client groups with advice for saving strategies, loans, wealth management, etc.
Image src: "https://user-images.githubusercontent.com/34673684/137431219-a5d99ac4-ce63-4435-8a49-4e19b09d0a07.png" align="center" alt="image"

### The sample dataset summarises the usage patterns of about 9000 active credit card users over the previous six months. The file contains 18 behavioural variables at the customer level.

### Data :

To download the data set, click the link below:[here](https://github.com/pik1989/MarketSegmentation/blob/main/Clustered_Customer_Data.csv)

### Methods employed

I performed segmentation on this dataset using five clustering algorithms.The following lists these algorithms.
K-Means Clustering(https://en.wikipedia.org/wiki/K-means_clustering)

- Agglomerative Clustering (scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
  Spectral clustering, DBSCAN clustering, and GaussianMixture Model-based clustering are available at https://scikit-learn.org/stable/modules/generated/sklearn.cluster.SpectralClustering.html and https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html, respectively.(https://en.wikipedia.org/wiki/Mixture_model)

### Finished Model:

Based on this clustering method, we have developed a streamlit application where we take client information and determine which cluster
