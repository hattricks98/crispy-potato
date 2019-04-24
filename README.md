# Crispy-Potato

# IMDB.com like website with basic CRUD and movie listing using C# (Asp.NET MVC / Asp.NET Core).

Simple Movie Database App. The application should hold movies, which are the main app entities. The functionality of the app should support creating, listing, editing and deleting movies. 
The application should persist the data into a database. Data validation and error handling is a plus but is not mandatory.

# Overview
1. ASP.NET framework (ASP.NET MVC + Entity Framework)
2. Razor view engine
3. Entity Framework ORM framework
4. MySQL Server database

# User Interface
This is the user interface should consists of the following pages (under the designated routes):

# Index Page
Route: / (GET)

List all movies.

# Create Page
Route: /create (GET and POST)

GET shows a form to create a film. POST saves the form data into the database as new film.

# Delete Page
Route: /delete/{id} (GET and POST)

GET shows a form to delete a certain film. POST confirms deleting a film and removes the film from the database.

# Edit Page
Route: /edit/{id} (GET and POST)

GET shows a form to edit a certain film. POST confirms editing a film and modifies the film in the database.

# Setup
 
 Before you start working, make sure you download all the dependencies (packages) required for each technology and set up the databases! Below are instructions on how to do this:
 
 The project will automatically resolve its NuGet dependencies (described in packages.config) using the NuGet package restore when the project is built. Just run the IMDB.sln after resolving all the dependencies on Visual Studio.
 

