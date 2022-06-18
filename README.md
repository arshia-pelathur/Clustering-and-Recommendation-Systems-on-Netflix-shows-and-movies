# Clustering-and-Recommendation-Systems-on-Netflix-shows-and-movies

The dataset used in this analysis consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings and votes interesting findings.


### Some interesting tasks that can be performed on this dataset

- Understanding what content is available in different countries
- Identifying similar content by matching text-based features
- Is Netflix increasingly focusing on TV rather than movies in recent years

### Column Description

1. Show_id                              = Indicating the ID's of Different TV Shows or Movies<br><br>
2. Type                                 = Indicates whether the recommended show is TV Show or Movie<br><br>
3. Title                                = Names of different TV Shows and Movies<br><br>
4. Director                             = Directors of respective TV Shows and Movies<br><br>
5. Cast                                 = Actors Featured in respective TV Shows and Movies<br><br>
6. Country                              = Country of Origin of Movie Make<br><br>
7. Date_Added                           = The Date on which that particular Movie or TV Show was added<br><br>
8. Release_Year                         = The year in which respective TV Show or Movie Released<br><br>
9. Rating                               = Recommended on the basis of different Parental Guidance<br><br>
10. Duration                            = Running of TV Show (in termms of Episodes) or Movie (in minutes)<br><br>
11. Genre                               = Classification or Type of TV Show or Movie fall under<br><br>
12. IMDB Weighted Average Vote          = Average Weighted Votes taken from IMDB<br><br>
13. IMDB Total Votes                    = Collective Votes taken from IMDB<br><br>
14. IMDB US Voters Rating               = Voters Rating on the basis of US users<br><br>
15. IMDB Non US Voters Rating           = Voters Rating on the basis of non-US users<br><br>
16. Reviews from users                  = Count of Reviews from Users<br><br>
17. Reviews from critics                = Count of Reviews from Critics


### Table of Content

1. Import Libraries

2. Data Preparation

      2.1 - Data Interpretation   
      2.2 - Missing Value Treatment
            
3. Exploratory Data Analysis

4. Data Cleaning

      4.1 - Replacement   
      4.2 - Scale the Data
            
5. Clustering

      5.1 - K Mean Clustering
      
            5.1.1 - Optimal value of K using Elbow Plot

            5.1.2 - Optimal value of K using Silhouette Score

            5.1.3 - Visualizing the Silhouette Score

            5.1.4 - Building the Cluster

            5.1.5 - Analyzing the Cluster
                
      5.2 - Hierarchical Clustering
      
            5.2.1 - Model Building

            5.2.2 - Dendrogram Plot

            5.2.3 - Cutting the Trees

            5.2.4 - Silhouette Score Method

            5.2.5 - Retrieving the Cluster
      
6. Recommendation Systems

      3.1 - Popularity Based Approach  
      
      3.2 - Content Based Recommendation
      
7. Conclusion


### Conclusion

1) We used a Netflix Dataset with Movies constituting 69.1% and TV Shows constituting 30.9%.

2) Netflix's content is divided into several categories that targets Adults, Teens, Older kids and Kids.

3) We used the K means and Hierarchical Clustering Algorithms to cluster our data. 

4) The optimal number of clusters we obtained is 2. Using this we built the Clusters and observed the following 
  
   - The Average Reviews from Users on TV Shows are more compared to Critics. 

   - Average IMDB US Voters Rating on TV Shows are more compared to IMDB Non-US Voters as goes with Movies.

   - Average IMDB US Voters on TV Shows are more compared to Movies indicating marginal preference of US Voters to TV Shows.

5) On the basis of Popularity Based Approach

   - The highest rated shows and movies on Netflix are not suitable for children below the age of 17. 
    
   - Average reviews from Netflix Users is more as compared to that of Critics.
   
   - US Raters give a higher Rating compared to Non US Raters.

6) On the Basis of Content Based Approach

   - We noted that Netflix could Recommend 5 Movies and TV Shows based on customer Interests.  
