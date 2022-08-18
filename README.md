
![Logo](https://techvidvan.com/tutorials/wp-content/uploads/sites/2/2021/06/machine-learning-project-movie-recommendation-system.jpg)


# Aim of the project
Ever wondered how Netflix or Hotstar recommends new movies based on the watch history, how Amazon or Flipkart suggests new products based on your order or search history? In this machine learning project, I build a recommendation system from the ground up to suggest movies to the user based on his/her preferences.

## DataSet: 
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/download?datasetVersionNumber=2
The dataset contains two CSV files, credits, and movies. The credits file contains all the metadata information about the movie and the movie file contains the information like name and id of the movie, budget, languages in the movie that has been released, etc.


## About Dataset
Data Source Transfer Details  that contains the metadata (cast, crew, budget, etc..) of the movie.
Several of the new columns contain json.
There's now a separate file containing the full credits for both the cast and crew.
All fields are filled out by users so don't expect them to agree on keywords, genres, ratings, or the like.

## Important Features 
We only need the following features:
- id
-title
-cast 
-crew columns 


## Run Locally

Clone the project

```bash
  git clone https://github.com/anilbarmola/TMDV-5000-movie-Recommendation--project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```



## Steps to  build a Movie Recommendation System using Machine Learning
The approach to build the movie recommendation engine consists of the following steps.
 - Perform Exploratory Data Analysis (EDA) on the data
 - Build the recommendation system
 - Get recommendations

### EDA
     a. get data 
     b. check null
     c. check duplicate values
     d. fetch related column
     e. preproceing 

### MODEL BUILDING 
Our movie recommendation engine works by suggesting movies to the user based on the metadata information. The similarity between the movies is calculated and then used to make recommendations. For that, our text data should be preprocessed and converted into a vectorizer using the CountVectorizer. As the name suggests, CountVectorizer counts the frequency of each word and outputs a 2D vector containing frequencies.
     a. buling a model(vactorization) 
     b. Bag of words(done)
     c.Cosine similarity 
We don’t take into account the words like a, an, the (these are called “stopwords”) because these words are usually present in higher amounts in the text and don’t make any sense.

There exist several similarity score functions such as cosine similarity, Pearson correlation coefficient, etc. Here, we use the cosine similarity score as this is just the dot product of the vector output by the CountVectorizer.

## Summary
In this machine learning project, we build movie recommendation systems. We built a content-based recommendation engine that makes recommendations given the title of the movie as input
### Content-based Filtering: 
These suggest recommendations based on the item metadata (movie, product, song, etc). Here, the main idea is if a user likes an item, then the user will also like items similar to it.




