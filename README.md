# Simplest-clustering-in-pyspark
Performed KMeans clustering in pyspark

Create a feature column using VectorAssembler.
Create a KMeans model using pyspark mllib library. We already know that there are 3 clusters.

But we can decide the value of k using Silhouette score method. 

Using Clustering Evaluator, we can evaluate silhouette score of the range of k values and choose the one with the highest score.
Here, also the highest score is for 3. 

You can use this model to predict a cluster of a new vector. Use predict function and input dense vector.
