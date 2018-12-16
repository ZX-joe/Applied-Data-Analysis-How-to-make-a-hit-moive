# How to Make a Hit Movie

Project for [Applied Data Analysis 2018](https://dlab.epfl.ch/teaching/fall2018/cs401/)

Team members: ZHOU Xiao, LIU Jiafan

**Final Jupyter Notebook**: [how-to-make-a-hit-movie.ipynb](http://nbviewer.jupyter.org/github/catJeff/ada-movie-analysis/blob/master/how-to-make-a-hit-movie.ipynb)

**Data Story**: See our [Github Page](https://howtomakeahitmovie.github.io/)

## Abstract
Today, movies are basically the most popular type of art and entertainment for us. People go to the cinema to watch a movie or buy it on Amazon, and give reviews and ratings on it. But for movie makers, movies are a type of business. Some blockbusters like "Avatar" have earned billions of dollars, while a lot of other movies are not as lucky as the highest-grossing ones. So we may wonder how to make a hit movie. We will try to use data analysis to answer this question. From the matadata, reviews, ratings and even subtitles of movies, we would like to find factors and features that make a movie to become best seller on Amazon or take high revenues from the box office.  

## Research questions
- What is the trend and evolution of movie ratings according to Amazon and TMDB?
  - For example, what is the most popular genre of movies at a time? How do the popularity change from time to time?
- What is the correlation between TMDB vote and Amazon reviews?
  - People's ratings for the movies and the movie products(e.g. DVDs, online video streams) may be different.
- Do good reviews and ratings lead to high revenues?
  - High revenues may not always mean good reputation. Is there a star effect of actors and directors that affects the revenues? Are there other factors?
- What are the factors and features that affect the ratings and sales of movies?
  - This is the final question we would like to answer. Our answer may help movie makers make a hit movie.



## Dataset
For the project, the datasets we analyse are as follows:

- [Amazon reviews dataset](http://jmcauley.ucsd.edu/data/amazon/index.html) contains totally 142.8 million product reviews (ratings, text, votes) and related metadata from Amazon. Among the huge data, we mainly use the 'Movies and TV' part for the inplementation of our ideas.

- [TMDB movie dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata) is a dataset we find on Kaggle. It contains metadata on thousands of movies, including the plot, cast, crew, budget, vote, revenues, etc.




## A list of internal milestones up until project milestone 2
- Collect the two datasets and find the movies that appear in every dataset. Our analysis is based on these common movies.
- Explore the dataset and get some description of the matadata, reviews, and ratings.
- Do some data cleaning to remove useless and redundant information. Merge and transform the datasets to a better form for further analysis.
- Design the machine learning methods to predict movie ratings or revenues from given features.

## A list of internal milestones up until project milestone 3

- Complete and optimize the machine learning approaches, utilize greedy selection to select features that affect movies profit and correponding Amazon reviews
- Implement more text data analysis with text processing approaches
- Analyze the features at higher level with detailed exploration and visualization
- Finish data story with exclusive analysis and intuitive visualization

## Contributions of group members
- LIU Jiafan: Amazon data analysis, numerical analysis, review text processing, website design and corresponding writing in data story
- ZHOU Xiao: TMDB data analysis, nonnumerical analysis, machine learning models, visualization, corresponding writing in data story
