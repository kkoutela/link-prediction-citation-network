# link-prediction-citation-network
Link Prediction in Citation Networks

The problem we had to solve is related to predicting links in a citation network. In our case, the citation network is a graph G(V, E), where nodes represent scientific papers and a link between nodes u and v denotes that one of the papers cites the other. Each node in the graph contains some properties such as: the paper abstract, the year of publication and the author names. From the original citation network some randomly selected links have been deleted. Your job is given a set of possible links to determine which of them have been deleted and thus they appear in the original network.

In this repository two files exist, the first one has to do with the creation of features that will be used to train the models 

## End up in 15 Features: 

1) Number of overlapping words in title  
2) Temporal distance between the papers  
3) Number of common authors  
4) Number of overlapping words in journal  
5) Number of overlapping words in abstract  
6) Cosine similarity of abstract  
7) Cosine similarity of title  
8) Cosine similarity of author  
9) Cosine similarity of journal

<b> Graph Based Features</b>

10) Jaccard similarity coefficient  
11) Preferential attachment score  
12) Adamic Adar Index  
13) Common neighbours  
14) Same Cluster (community)  
15) Community resource allocation  

## In the second repository we perform feature selection and afterwards we train the following algorithms:

- SVM
- KNN
- Decision Trees
- Radom Forest Classifier
- AdaBoost
- Bagging Classifier
- Gradient Boosting Classifier
- Gausian NB
- Linear Discriminant Analysis
- MLP Classifier
