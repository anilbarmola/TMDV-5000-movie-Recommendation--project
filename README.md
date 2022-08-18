
![Logo](https://techvidvan.com/tutorials/wp-content/uploads/sites/2/2021/06/machine-learning-project-movie-recommendation-system.jpg)


# Aim of the project

## DataSet: 
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/download?datasetVersionNumber=2


## About Dataset
Data Source Transfer Details
Several of the new columns contain json. You can save a bit of time by porting the load data functions [from this kernel]().
Even in simple fields like runtime may not be consistent across versions. For example, previous dataset shows the duration for Avatar's extended cut while TMDB shows the time for the original version.
There's now a separate file containing the full credits for both the cast and crew.
All fields are filled out by users so don't expect them to agree on keywords, genres, ratings, or the like.
Your existing kernels will continue to render normally until they are re-run.
If you are curious about how this dataset was prepared, the code to access TMDb's API is posted here. https://gist.github.com/SohierDane/4a84cb96d220fc4791f52562be37968b

## Steps For EDA & Model Building
Follwing are the steps which I am going to take while doing this project

### EDA
     a. get data 
     b. check null
     c. check duplicate values
     d. fetch related column
     e. preproceing 
### MODEL BUILDING 
     a. buling a model(vactorization) 
     b. Bag of words(done)
     c.Cosine similarity 


## ML Approach : Cosine similarity between two vectors of an inner product space



