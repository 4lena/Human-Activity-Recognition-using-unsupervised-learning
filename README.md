# Human Activity Recognition Using Unsupervised Learning

## About The Project
Recognize human activity using unsupervised learning. The project started with preprocessing the data by scaling it using Z-mean standardization. Then, a PCA model was created to reduce the dimensionality of the data. The number of principal components was determined to explain at least 95% of the variance in the original data.
Next, the transformed data were used to perform clustering using three different algorithms: KMeans, agglomerative, and spectral. 
To evaluate the performance of each clustering algorithm, two metrics were used: adjusted Rand index (ARI) and silhouette score. Finally, the elbow method was used to find the optimal number of clusters for the KMeans model.

## Dataset source
https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones

## Built With

* [![My Skills](https://skills.thijs.gg/icons?i=python,colab)](https://skills.thijs.gg)
* <img width="50" alt="logo" src="https://camo.githubusercontent.com/0b93f22ac70b7983e9915edf30ddc1a15713b2c310a214c2996dff49b410b949/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3236373335363138303036343530313736302f3738313937313935303438363239303433322f476f6f676c655f436f6c61626f7261746f72792e737667">
