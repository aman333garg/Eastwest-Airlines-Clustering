# Eastwest-Airlines-Clustering
Hierarchical and K-Means clustering applied on East West Airlines customers for audience segmentation and suggesting remarketing actions.

First we need to standardize the data before applying any clustering technique because as we can see in the output below, the scales are very different across variables.

## Heirarchichal Clustering:
The Dendrogram with Euclidean distance and Ward’s method is below. It shows that around 4-6 clusters are appearing. For our analysis, we will go with 5 clusters for Hierarchical Clustering.

![image](https://user-images.githubusercontent.com/30589320/235450601-3cd4cae4-3e7e-4e6a-bfdc-f5f4da0f5b3e.png)

![image](https://user-images.githubusercontent.com/30589320/235450616-6cdacb36-ad0e-4728-b939-211e84e984d8.png)

The parallel coordinate plot below shows the clusters on a graph with their variations across variables. This will help us see the characteristics to give meaningful names to the clusters.

![image](https://user-images.githubusercontent.com/30589320/235450741-41811d20-b3c8-49d4-9d1e-d60b23ae4d42.png)

Based on above graph, we can infer the cluster characteristics as shown in the below table and then come up with appropriate labels for each.
Color coded various characteristics of observations to identify labels.
Dark Green – High, Light Green – Good, Yellow – Average, Red –Low

![image](https://user-images.githubusercontent.com/30589320/235451064-457999ae-72f7-4ce3-8dc5-df652fa7ec78.png)

We decide the optimal number of clusters in K-Means by plotting the elbow plot for distortion. The elbow occurs at k=7 as shown below.

![image](https://user-images.githubusercontent.com/30589320/235450463-53a24475-89b0-4ba3-ab86-57641576bed9.png)

Labelling the clusters based on their characteristics and then recommending business actions for the cohort.

![image](https://user-images.githubusercontent.com/30589320/235451192-6015a808-b2d7-488d-abea-918937c8a745.png)
