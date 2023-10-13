# Koding-Kitchen
An app to allow users to quickly find  tasty recipes based on their current cravings, food type, diet, or  ingredients.

## Description

This is a group project to design an interactive app where users can search for recipes. This app uses two server-side APIs for giphy’s and recipe retreival. They are https://api.giphy.com and https://api.spoonacular.com. Users will enter a food type to query on, or they can enter ingredients. The software will retrieve recipes that match their input. The app uses client-side storage to store persistent data and uses modals for input. This project was the first introduction to implementing agile development methodologies and Git branch workflow with pull requests. Various merge conflicts were resolved through collaboration. This project was presented to our cohort and instructional staff and deployed on git hub pages.

[![License](https://img.shields.io/badge/License-n/a-n/a.svg)](n/a)

# Git Hub Repository
https://github.com/tasshroll/best-blog-site

# Deployed App

https://best-tech-blog-app.herokuapp.com/

# Webpage

Link to Deployed Application:
 https://ggdave.github.io/Koding-Kitchen/

Link to GitHub Repo
 https://github.com/GGDave/Koding-Kitchen



# Screenshot

Initial Page

<img src="./images/Screenshot%202023-04-06%20at%207.31.09%20PM.png" alt="Recipe Home Page" width="700">


Personalized recipes

<img src="./images/Screenshot-2nd-page.png" alt="Recipe 2nd Page" width="700">


## User Story

```md
AS A user who likes to cook
I WANT a fast and easy personalized web site 
SO THAT I can retrieve and save favorite recipes
```

## Acceptance Criteria

```md
GIVEN a recipe site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which prompts me for a food query
WHEN I enter in a food cuisine type on the homepage
THEN I am taken to a page of recipe titles with images that match the food query
WHEN I am viewing the list of 10 recipe titles and images
THEN I see Chef Gordon Ramsey giphy's displayed on the side for a few seconds.
WHEN I enter in ingredients, 
THEN I am taken to a page of recipe titles with images that contain my ingredients
WHEN I choose to click the checkbox
THEN that recipe title is added to my "Saved Recipes" at the bottom of the page
WHEN I click on the "Show 10 More Recipes Like These"
THEN I can view 10 new and different recipes
WHEN I click on any recipe image or title
THEN I am presented with the full recipe
```

## Collaborators
Developers: David Flores, Bill Hamilton, Breeann Bond, Tifni Shroll






# best-blog-site

Blog site application that allow developers to publish blog posts and comment on other posts about technical concepts, recent advancements, and new technologies.

# Description

This application follows MVC methodology to relate the user front end to back end SQL data models. The three tables used to track data are Blog, User, Comment. Users are presented a homepage which includes existing blog posts if they exist. Users are prompted to signup/login to view blog details, create and delete blogs, and make comments on other blogs. The app will authenticate user credentials and save their session. The app uses the following packages: express-handlebars, mySQL2, Sequelize, and bcrypt. 


[![License](https://img.shields.io/badge/License-n/a-n/a.svg)](n/a)

# Git Hub Repository
https://github.com/tasshroll/best-blog-site

# Heroku Deployed App

https://best-tech-blog-app.herokuapp.com/


# Screenshots

Visual for associations between 3 tables in blog_db: Blog, Comment, User

PK = Primary Key, FK = Foreign Key

<img src="./Assets/blog_db_tables.png" alt="Database Tables" width="500">

Homepage display of all blogs

<img src="Assets/homepage.png" alt="Homepage display of all blogs" width="800">

Profile display of all users contributions

<img src="Assets/profile_page.png" alt="Profile display" width="500">

Comment display

<img src="Assets/comment_page.png" alt="Comment display" width="700">

## Table of Contents

[Installation & Usage](#installation--usage)

[User Story](#user-story)

[Acceptance Criteria](#acceptance-criteria)

# Installation & Usage

Run from Heroku. 

To run on command line do these steps:

1. Set up the environment by installing node package manager:

	* npm i 


2. Create the schema from the MySQL shell.

	* mysql
	* source {path}/schema.sql 
	* exit


3. Seed the database from the command line, OPTIONAL check of the contents of product table:

	* node ./seeds/seed.js
	* mysql

4. Start the server. Response is, "App listening on port 3001!"

	* node server.js


## User Story

```md
AS A user who wants to cook
I WANT a fast and easy personalized web site 
SO THAT I can reteive and favorite recipes to make
```

## Acceptance Criteria

```md
GIVEN a recipe site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which prompts me for a food query
WHEN I enter in a food cuisine type on the homepage
THEN I am taken to a page of recipe titles with images that match the food query
WHEN I am viewing the list of 10 recipe titles and images
THEN I see Chef Gordon Ramsey giphy's displayed on the side for a few seconds.
WHEN I enter in ingredients, 
THEN I am taken to a page of recipe titles with images that contain my ingredients
WHEN I choose to click the checkbox
THEN that recipe title is added to my "Saved Recipes" at the bottom of the page
WHEN I click on the "Show 10 More Recipes Like These"
THEN I can view 10 new and different recipes
WHEN I click on any recipe image or title
THEN I am presented with the full recipe
```

## Contributors
Tutors: Vinnie Lopez (for edit hep with blog) 
& Matthew Calimbas (routes)