# Unit 3 - Data for Social Good Project 

## Introduction 

Software engineers develop programs to work with data and provide information to a user. Each user has different needs based on the information they are looking for from data. Your goal is to create a data analysis program for your user that stores and analyzes data to provide the information they need. 

## Requirements 

Use your knowledge of object-oriented programming, one-dimensional (1D) arrays, and algorithms to create your data analysis program: 
- **Write a class** – Write a class to represent your user or business and store and analyze their data with no-argument and parameterized constructors. 
- **Create at least two 1D arrays** – Create at least two 1D arrays to store the data that your user needs information about. 
- **Write a method** – Write a method that finds or manipulates the elements in a 1D array to provide the information your user needs. 
- **Implement a toString() method** – Write a toString() method that returns general information about the data (for example, number of values in the dataset). 
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions. 

## User Story 

Include your User Story you analyzed for your project here. Your User Story should have the following format: 

> As an movie enthusiast, <br> 
> I want to analyze rated movies, <br> 
> so that I can I can see which movies are most popular. 

## Dataset 

Include a hyperlink to the source of your dataset used for this project. Additionally, provide a short description of each column used from the dataset, and the data type. 
 

Dataset: https://github.com/sankha1998/tmdb_top_movies
- **Tile** (String) - official title of the movie 
- **Overview** (String) - a breif summary of the overall movie
- **voteCount** (int) - amount of people who voted for the specific movie
- **rating** (double) - The average of ratings between all users’ votes based on a scale of 10

## UML Diagram 

Put and image of your UML Diagram here. Upload the image of your UML Diagram to your repository, then use the Markdown syntax to insert your image here. Make sure your image file name is one work, otherwise it might not properly get display on this README. 

UML Diagram for my project:
(https://docs.google.com/drawings/d/1YSpt_MiVWsyXfwCTuDf7Jj75hRqUcVAcYKOSrj39yco/edit?usp=sharing) 

## Description 

Using a data set about movies, our user wants to find the best movie to watch based the information given about the movies. Our goal is to provide the user the title, overview, vote count, and ratings of different movies. This allows the user to see the information and chose the movie they like best to watch.
First it declares the instance variables title, overview, vote count, and rating. Then, the Movie() method uses the this keyword to refer to the instance variables or the current object. There are four get methods used to return the value of the variable name.The toString method is used to return the information being printed into the console.
Then, the userStory class creates an array of movies by putting the files together.The constructor uses the createMovie() method to take the information from the files to create a Movie object. Then by using a for-loop, the information is printed through the local variable tempMovies.
Finally, the toString() method uses a local variable to store the string that will be printed. An enhanced for loop traverses the array and adds a new line after each element.

