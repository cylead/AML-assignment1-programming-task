### Intro
This is te assignment 1 programming task for the course DD2434 Machine Learning, Advanced at KTH. We visualize a dataset using 3 dimensionality reduction methods: PCA, MDS and Isomap.

Tools: Python (libraries: numpy, pandas, matplotlib, sklearn, scipy etc.), Jupyter Notebook.
### The dataset
The ["zoo" dataset](https://archive.ics.uci.edu/ml/datasets/zoo) in the UCI ML repository.

#### Dimensionality Algorithms
#### PCA
The sklearn module is used to perform PCA.
#### MDS
The algorithm is implemented by myself. 
Random forest classification is used to calculate the importances of features and then calculate the weighted distance matrix.  
#### ISOMAP
The algorithm is implemented by myself. Floyd-Warshall algorithm is used to calculate the shortest path distance.
To get optimum k in the k-nearst connection part, I plot the results of k from 18 to 97 and from 37 to 96 respectively for the nomal isomap and isomap with weighted distance matrix input.

### Analysis
The detailed analysis can be found in the ![report](https://github.com/yangBryants/AML-assignment1-programming-task/blob/main/report.pdf)
