# Iris-Dataset-

Dataset CSV - https://www.kaggle.com/datasets/uciml/iris

Solution Data Analysis & Machine Learning K-Means Clustering :

https://github.com/shasha0982/Iris-Dataset-/blob/main/My_Project_Iris_Species.ipynb

https://github.com/shasha0982/Iris-Dataset-/blob/main/iris_report.html ( download to see data analysis )

https://github.com/shasha0982/Iris-Dataset-/blob/main/iris_compare.html ( download to see data analysis )


<a href="https://websitedownloader.com/download-file-from-url-online/">Copy Link & Download Data Analysis Report</a>


 if you using github, at that file you can see edit this file and at the left "download raw file" . Click download raw file to download data analysis report.


# Path 

Import Libraries --> Data Inspection ---> Using SweetViz & Neptune AI for Data Analysis / Machine Learning K-Means Clustering 



# Conslusion from this project 

Explanation :

Data Analysis : 

Data analysis is like solving a puzzle with numbers and information. Imagine you have a big pile of puzzle pieces, and each piece represents a piece of data. Your job is to arrange these pieces in a way that makes sense, revealing a picture or pattern hidden within them. You might sort, organize, and compare the pieces to see how they fit together and what story they tell. Data analysis does the same thing but with numbers, statistics, and information instead of puzzle pieces. It helps you understand what the data is trying to tell you and make informed decisions based on that understanding.


Correlation Coefficient :

The correlation coefficient, which measures the strength and direction of a relationship between two variables, ranges from -1 to 1.

A correlation coefficient of 1 indicates a perfect positive correlation, meaning that as one variable increases, the other variable also increases proportionally.
A correlation coefficient of -1 indicates a perfect negative correlation, meaning that as one variable increases, the other variable decreases proportionally.
A correlation coefficient of 0 indicates no linear relationship between the variables.


Clustering: 

* In this case, the data doesn't have any labels or categories assigned to it. The goal is for the model to group or cluster the data into different sets based on similarities it finds in the data itself. An example would be grouping photos of different people's faces without being told who they are.


From Data Analysis Report :

sepal length (cm) - The most sepal length(cm) value is 6.0 cm with estimate 18% missing values

sepal width (cm) - The most sepal width(cm) value is 3.0 cm with estimate 25% missing values

petal length (cm) - The most petal length(cm) value is 1.0 cm with 30% missing values

petal width (cm) - The most petal width (cm) value is 0.1 cm with estimate 28% missing values 



From correlation report showed a correlation coefficient of 1 signifies a very strong and positive relationship between the variables under consideration, indicating that changes in one variable are highly predictive of changes in the other.



Summarization from machine learning k-means clustering report : 

We conducted k-means clustering analysis on the iris dataset to uncover underlying patterns in the data. The analysis yielded valuable insights, which are summarized below:


Inertia (WCSS):

Inertia, also known as Within-Cluster Sum of Squares (WCSS), measures the dispersion of data points within their assigned clusters.
A lower inertia value, as observed in our analysis (78.85), indicates that data points are closely grouped around the centroids of their respective clusters.
This suggests that the clusters are relatively compact and well-defined, which is a desirable outcome in clustering analysis.


Silhouette Score:

The silhouette score is a metric used to evaluate the quality of clustering.
It measures how well each data point fits into its assigned cluster compared to other clusters, ranging from -1 to 1.
Our analysis produced a silhouette score of 0.55, indicating moderately good clustering performance.
A score around 0.5 is generally considered reasonable, suggesting that our clustering results capture meaningful patterns in the data.


K-means WCSS:

The K-means Within-Cluster Sum of Squares (WCSS) is synonymous with the inertia value mentioned earlier.
It quantifies the sum of squared distances between data points and the centroids of their respective clusters.
Our analysis revealed a K-means WCSS value of 78.85, reaffirming the compactness and separation of clusters observed through inertia.


Conclusion:

The k-means clustering analysis on the iris dataset demonstrates promising results, with well-defined clusters and meaningful patterns identified within the data. While the clustering performance is moderately good, there may still be opportunities for further refinement and improvement. Overall, this analysis provides valuable insights for understanding the underlying structure of the iris dataset, facilitating informed decision-making and potential applications in various fields.




