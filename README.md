# Myopia_Clusters

In this assignment, I applied what i learned about unsupervised learning by fitting data to a model and using clustering algorithms to place data into groups. Then, I created a visualization that shares my findings.

In part 1 I prepared the data
* I Read myopia.csv into a Pandas DataFrame.

<img width="645" alt="Screenshot 2022-08-09 13 43 50" src="https://user-images.githubusercontent.com/100292828/183724325-46b5c7db-58fc-4a0d-8de4-7bf2b415f2c5.png">

* I Removed the "MYOPIC" column from the dataset.

In part 2 I applied Dimensionality Reduction
Dimensionality was then reduced using PCA (Principal Component Analysis) and then data clustering using t-SNE (t-distributed Stochastic Neighbor Embedding) was completed. By looking at the scatter plot, it can be seen that there are 5 distincts clusters.

<img width="287" alt="Screenshot 2022-08-09 13 27 16" src="https://user-images.githubusercontent.com/100292828/183726480-99605d82-015b-4c35-9e3b-02f38aebf475.png">

 In Part 3 I Performed a Cluster Analysis with K-means
 I Created an elbow plot to identify the best number of clusters

<img width="335" alt="Screenshot 2022-08-09 13 27 43" src="https://user-images.githubusercontent.com/100292828/183725854-d613235c-e862-4ea6-b009-2b1e185925ec.png">

### Recommendation

By observing the Elbow plot, it seems like the Elbow is at 3 suggesting that numbers of clusters should be 3,that is k=3. Based on the result of the clustering algorithm, the patients can be clustered into 3 groups.

<hr>
Contact : 

* tourteau.christian@gmail.com
* https://www.linkedin.com/in/christian-tourteau/
