# Netflix_Movies_and_TV_Shows_Clustering

The primary goal of this project is to analyse and provide appropriate recommendations.This process would involve grouping the data into various clusters using NLP techniques in order to attain enhanced user experience with the help of a recommender system. Clustering algorithms have been applied such as k-means, hierarchical clustering, or density-based spatial clustering which helps to group similar movies and TV shows based on their aspects. The clusters formed were then analysed to acknowledge mutual patterns and characteristics.

The project would help understand Netflix's content and would help the organization make the services better to serve their clients effectively.

Problem Statement 

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

**EDA Insights:**


*   A lot of content has been added in the recent years, but from 2016 onwards a higher numer of TV Shows and Movies have been added in which Movies are higher in number.
*   By looking at the data about addition of content over the year, a higher numer of addition of content has been done during the first and last few months of the year.
*   On analysing the data, it was found that Movies are being watched more than TV Shows
*   Of all the TV Shows present, a majority of them have only 1 season.
*   It can be seen that most of the content available is from the Genre Documentaries and Stand-up Comedy.
*   Marcus Raboy and Jay Karas has the highest number of Movies and TV Shows present on the platform


**Clustering and Recommender System Insights:**


*   After applying K-means clustering on the dataset, we get a value as k=4 which is the optimal number of clusters formed.
*   The Silhouette Score for evaluation metric was chosen as it provides a comprehensible result and is less sensitive towards the shape of clusters.
*   A recommender system has been built that can assist the organisation to improve user experience and also enhance engagement in content of several genres based on their similarity scores.


**Future Work:**


*   An addition of data about Runtime,IMDB Scores,Number of people watched etc. would help elaborate the efficiency of the recommender system to significally increment user experience and engagement.
*   Introduction of TV Shows of good content would help lessen the gap between the number of Movies and TV Shows that are available to wach on the platform which would further promote user engagement.
