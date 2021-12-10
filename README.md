# anishathakrar.github.io
# plot

### COVID-19 Document Clustering

With the increase in number of COVID-19 cases, it is difficult to keep up with new information on the virus. This requires proper organization of documents and hence defining a procedure to organize literature related to COVID-19 using machine learning algorithms in order to group similar papers is important.

The dataset was collected from a publicly available COVID-19 Open Research Dataset Challenge on Kaggle. This is a resource of over 500,000 scholarly articles, including over 200,000 with full text, about COVID-19, SARS-CoV-2, and related coronaviruses. It is associated with bibliographic features like title, abstract, author, publication date, etc. Since the dataset is extremely large, 10,000 random samples have been considered to save computational resources.

Steps taken are:

1. Use pool of raw data to extract useful information by means of natural language processing techniques and unsupervised machine learning algorithms.
2. Create clusters to group papers based on similarity.
3. Discover the underlying topic in each generated cluster via topic modeling.
4. Use a combination of dimensionality reduction and clustering techniques to achieve goal of easy access to every paper.
5. Labeled clusters are derived using a combination of dimensionality reduction and clustering techniques such as PCA, TSNE, K-Means and LDA.

Future work:

1. We can implement DBSCAN algorithm and compare the results for K-Means and DBSCAN.
2. We can also include papers from all languages. This gives us an experience from different geographic locations in dealing with COVID-19.
3. As a part of dimensionality reduction, we can use the ensemble of PCA and manifold learning. This captures the linear, nonlinear, local and global features in the original dataset.
4. Incorporating keyword search with document clustering will make it more efficient and less time consuming.
