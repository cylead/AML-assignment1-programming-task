#### Main task
We visualize a dataset using 3 dimensionality reduction methods: PCA, MDS and Isomap.
#### The dataset
The ["zoo" dataset](https://archive.ics.uci.edu/ml/datasets/zoo) in the UCI ML repository.
#### Alogrithm implementation
The code is written in python and through Jupyter notebook. As long as the corresponding python library is installed, it can be run.
##### PCA
The sklearn module is used to perform PCA.
##### MDS
The algorithm is written by myself. 
Random forest classification is used to calculate the importances of features and then calculate the weighted distance matrix.  
##### ISOMAP
The algorithm is written by myself. Floyd-Warshall algorithm is used to calculate the shortest path distance.
To get optimum k in the k-nearst connection part, I plot the results of k from 18 to 97 and from 37 to 96 respectively for the nomal isomap and isomap with weighted distance matrix input.
