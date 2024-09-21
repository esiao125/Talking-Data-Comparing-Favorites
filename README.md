# Talking Data: Comparing Favorites Starter Code
Fork this project to get started on the project.

### Project Requirements
Your project should:
- Use a variable to store and print the data of your favorite movie.
- Use .loc to filter the data set to a genre, and store it in a new variable.
- Calculate the min, max, mean, and median of a column.
- Print how the min, max mean, and median compare to your favorite movie's value.
- Create a histogram and use a print statement to describe it.
- Create a scatter plot and use a print statement to describe the relationship between two variables.

### Extensions
You can extend your project further by:
- Plot your favorite movie
- Explore more data
- Visualize data creatively

###  Attributions
The rotten_tomatoes_movies.csv data was originally scrapped by Stefano Leone and is available on Kaggle for CC0:Public Domain Use: https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset?select=rotten_tomatoes_movies.csv

*If you used any code, ideas, images, or resources from another person or group of people, tell us about it here. Make sure it is in the public domain, has a license that allows you to use it, or is one of your own.

---

## File Overview

### ← main.py
This is where you will write your main program.

### ← README.md
README.md file give you more documentation and information about a program. They are super helpful for describing what a program should do, any issues you've encountered, changes you want to make, and more. 

### ← rotten_tomatoes_movies.csv
This is a csv file containing data scraped from Rotten Tomatoes by Stefano Leone. The data was made modified to make student usability easier. Modifications include: Creating the year_released column based on original_release_date, dropping NA values, and selecting out the columns: movie_title, year_released, critic_rating, audience_rating, genres.