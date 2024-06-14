# CAPSTONE-PROJECT--Netflix-Movies-And-Tv-shows-Clustering
![N](https://mir-s3-cdn-cf.behance.net/project_modules/hd/fb762791877129.5e3cb3903fb67.gif)

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Table of Contents   
- [Abstract](#Abstract)
- [Project Files Description](#Project-Files-Description)
- [About the Dataset](#About-the-Dataset)      
- [Project Work Flow](#Project-Work-Flow) 
- [Purpose of the Analysis ](#Purpose-of-the-Analysis)
- [Conclusion](#Conclusion)

  
![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Abstract:
Netflix, a premier streaming service, caters to over 220 million subscribers worldwide with an extensive collection of movies and TV shows. Utilizing sophisticated algorithms and data analytics, Netflix personalizes content recommendations, aiming to enhance user satisfaction, boost engagement, and reduce subscriber churn, maintaining its dominant position in the entertainment industry.

The primary objective of this project is to analyze the Netflix Dataset encompassing movies and TV shows up to 2019, obtained from the third-party search engine, Flixable. The overarching aim is to leverage NLP techniques to categorize this content into meaningful clusters, ultimately enhancing the user experience through a recommendation system. This strategic approach is designed to mitigate subscriber churn for Netflix.

In addition to recommendation system development, this project includes an in-depth examination of the dataset to unearth valuable insights and emerging trends within the streaming entertainment industry.

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Project Files Description
This Project includes 1 colab notebook.

### Executable Files:
[NETFLIX MOVIES AND TV SHOWS CLUSTERING.ipynb](https://github.com/Harshita-Pokharna/CAPSTONE-PROJECT--Netflix-Movies-And-Tv-shows-Clustering/blob/main/ML.ipynb)- Includes all codes required

### Output:
[Google Colab](https://github.com/Harshita-Pokharna/CAPSTONE-PROJECT--Netflix-Movies-And-Tv-shows-Clustering/blob/main/ML.ipynb)- All the outputs are visible in the provided colab notebook.
### Input Files:
NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv

### Data Source:
Almabetter

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## About the Dataset
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine. 
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
  
![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Project Work Flow

The project was carried out in the following step-by-step process:
* Importing Necessary Libraries
* Loading the Dataset
* Exploring Dataset
* Data Wrangling
* Exploratory Data Analysis (EDA)
* Hypothesis Testing
* Data Preprocessing
* Creating Clusters
* Dimensionality Reduction
* Clustering Algorithms
* Content-Based Recommender System
* Conclusion

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Purpose of the analysis

This project aims to analyze the Netflix Dataset of movies and TV shows until 2019, obtained from the third-party search engine Flixable. The primary objective is to group the content into relevant clusters using NLP techniques to enhance the user experience through a recommendation system. This system will help mitigate subscriber churn for Netflix, which currently boasts over 220 million subscribers.

Moreover, this project seeks to uncover valuable insights and trends in the streaming entertainment industry by analyzing the dataset.

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Conclusion
* In this project, we tackled clustering Netflix shows into distinct categories based on their similarity. The dataset contained 7787 records with 11 attributes.

* We began by addressing missing values and conducting exploratory data analysis (EDA). We found that Netflix primarily hosts movies, with an exponentially growing number of shows, predominantly from the United States, targeting adult and young adult audiences.

* We clustered the data using attributes like director, cast, country, genre, and description, which were tokenized and transformed into numerical features using TFIDF vectorization, resulting in 20,000 attributes. To handle dimensionality, we applied Principal Component Analysis (PCA).

* Using the k-means clustering algorithm, we identified 6 optimal clusters through the elbow method and Silhouette score analysis. We also employed Agglomerative clustering, determining 2 optimal clusters based on dendrogram visualization.

* For user recommendations, we developed a content-based recommender system using a cosine similarity matrix, generating 10 recommendations based on watched shows.

* This project encompassed data preprocessing, dimensionality reduction, clustering with k-means and Agglomerative algorithms, and the development of a content-based recommender system.
