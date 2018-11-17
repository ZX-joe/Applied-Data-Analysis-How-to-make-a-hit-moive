# How to Make a Hit Movie

## Abstract
Today, movies are basically the most popular type of art and entertainment for us. People go to the cinema to watch a movie or buy it on Amazon, and give reviews and ratings on it. But for movie makers, movies are a type of business. Some blockbusters like "Avatar" have earned billions of dollars, while a lot of other movies are not as lucky as the highest-grossing ones. So we may wonder how to make a hit movie. We will try to use data analysis to answer this question. From the matadata, reviews, ratings and even subtitles of movies, we would like to find factors and features that make a movie to become best seller on Amazon or take high revenues from the box office.  

## Research questions
- What is the trend and evolution of movie ratings according to Amazon?
  - For example, what is the most popular genre of movies at a time? How do the popularity change from time to time?
- What are the features of helpful reviews of a movie?
  - What kind of reviews are helpful? How can we filter reviews of low quality to get the real ones?
- What is the correlation between TMDB vote and Amazon reviews?
  - People's ratings for the movies and the movie products(e.g. DVDs, online video streams) may be different.
- Do good reviews and ratings lead to high revenues?
  - High revenues may not always mean good reputation. Is there a star effect of actors and directors that affects the revenues? Are there other factors?
- (Optional) Do the features in subtitles affect the quality of a movie?
  - For example, different genres of movies may have different pace and different keywords in their lines. We can get new information from the movie subtitles.
- What are the factors and features that affect the ratings and sales of movies?
  - This is the final question we would like to answer. Our answer may help movie makers make a hit movie.



## Dataset
For the project, the datasets we analyse are as follows:

- [Amazon reviews dataset](http://jmcauley.ucsd.edu/data/amazon/index.html) contains totally 142.8 million product reviews (ratings, text, votes) and related metadata from Amazon. Among the huge data, we mainly use the 'Movies and TV' part for the inplementation of our ideas.

- [TMDB movie dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata) is a dataset we find in kaggle. It contains metadata on thousands of movies, including the plot, cast, crew, budget, vote, revenues, etc.

- [OpenSubtitles dataset](https://icitdocs.epfl.ch/display/clusterdocs/OpenSubtitles) covers a total of 152,939 movies or TV episodes determined by their IMDb identifier. We will focus on the English version and go into details of timelines and dialogue features of a movie and correlate these features with existing movies in Amazon and TMDB dataset.



## A list of internal milestones up until project milestone 2
- Collect the three datasets and find the movies that appear in every dataset. Our analysis is based on these common movies.
- Explore the dataset and get some description of the matadata, reviews, ratings, and subtitles.
- Do some data cleaning to remove useless and redundant information. Merge and transform the datasets to a better form for further analysis.
- Design the machine learning methods to predict movie ratings or revenues from given features.
