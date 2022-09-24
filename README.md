# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING
<h2> Project Files Description</h2>
This Project includes 1 colab notebook, 1 technical documentation as well as 1 presentation:

<h4> Executable Files:</h4>
NETFLIX MOVIES AND TV SHOWS CLUSTERING.ipynb - Includes all functions.
<h4> Output:</h4> 
Google Colab - All the outputs are visible in the provided colab notebook.
<h4> Input Files:</h4> 
NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv - Input dataset having information about different shows/movies available on Netflix.

<h2> Problem Statement</h2>

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a 
third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has 
nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number 
of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. 
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings. In 
this project, you are required to do: 
* Exploratory Data Analysis 
* Understanding what type content is available in different countries 
* Is Netflix has increasingly focusing on TV rather than movies in recent years
* Clustering similar content by matching text-based features.


<h2> Introduction </h2>
This project aims to develop a Netflix movie recommendation system based on similarities within movies/ TV shows. The purpose of this 
study is to analyze a dataset from the Netflix database in order to analyze the similarities among the movies/ TV shows. We have all found 
ourselves scrolling endlessly looking for what to watch so this project might help with that. There is no information provided about the 
preferences of users, so what would be one's recommendation after watching a certain movie is what we are estimating.


<h2> Attributes </h2>

* show_id : Unique ID for every Movie / Tv Show
* type : Identifier - A Movie or TV Show
* title : Title of the Movie / Tv Show 
* director : Director of the Movie
* cast : Actors involved in the movie / show
* country : Country where the movie / show was produced
* date_added : Date it was added on Netflix
* release_year : Actual Release Year of the movie / show
* rating : TV Rating of the movie / show
* duration : Total Duration - in minutes or number of seasons
* listed_in : Genere
* description: The Summary description

<h2> Steps involved:</h2>
The full code for this article can be found here. It is implemented in Python and uses different clustering algorithms. The general 
approach I used can be summarized as follows:

Performing data cleaning and pre-processing: In this step, I checked and corrected missing and duplicate values since missing and 
duplicate variables can negatively affect machine learning algorithms (many algorithms do not tolerate missing data). 

Exploratory data analysis: This was to gain important statistical insight from the data and evaluate the distributions of the 
attributes, correlations between the attributes, and the target variable. 

Clustering: In machine learning, clustering or cluster analysis is a technique that groups unlabeled data into groups. In 
other words, it is a method of grouping similar data points into clusters.  Similar objects are grouped in groups that have little or 
no similarity with another group. Due to its unsupervised nature, there is no supervision provided to the algorithm, and it deals with 
unlabeled data.  As a result of this clustering technique, each cluster or group is assigned a cluster-ID. Large and complex datasets 
can be simplified through the use of this identifier.

NLP (Natural Language Processing):  NLP makes it possible for computers to read text, hear speech, interpret it, measure sentiment and 
determine which parts are important.

<h2> Conclusion:</h2>
By analyzing movie and TV show information, appropriate recommendations can be made. The same model can also be used to make valuable 
recommendations to consumers in other fields. As a result, Netflix's recommendations will be more reliable. In addition, users will be 
less likely to skip watching a movie or TV show due to better movie and TV show selection times.
