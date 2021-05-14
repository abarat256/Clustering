# Clustering

Datasets used : Aggregation, Compound, R15, Jain, Path-based, Spiral, D31 
All these datasets are available online for educational use.
Note: Permission might be required to access them. 
For plots I have used Weka

1 Clustering
------------------


You have been provided with the following 8 2-dimensional datasets for clustering: Aggregation, Compound, Path-based, Spiral, D31, R15, Jain, Flames. First two columns are the features and the third column is the class label. In all your experiments, make sure that you are not giving the third column also as input to the clustering algorithm. You need to turn in the visualizations of your results for each question.
1. Convert all 8 datasets into ARFF format. 

2. Visualize all 8 datasets. 
You need to turn in all your plots. 
Analyze each dataset by visualization and explain how these clustering algorithms will perform in these data (with reasons) : K-means, DBSCAN, hierarchical clustering with single link and complete link. 

3. Run K-means with R15 dataset. Set k = 8. Report the cluster purity. 
Vary the value of k from 1 to 20 and study the eﬀect of k on cluster purity. 
Plot a graph which explains your study.

4. Run DBSCAN with Jain dataset. Again report cluster purity. 
Study the eﬀect of minpoints and epsilon on cluster purity. 

5. Run DBSCAN and hierarchical clustering on Path-based, Spiral and Flames. Compare their performance on each dataset. 
For hierarchical clustering, you need to experiment with all types of linkages available in Weka to ﬁnd the one that best suits the data.

6. Run K-means with D31 dataset. 
Can you recover all 31 clusters with k = 32? If not, can you recover all clusters by increasing the value of k? 
What happens when you apply DBSCAN? Apply hierarchical clustering with Ward’s linkage. How does it perform?
