# SwiftyMovies
Assignment for ILI.DIGITAL

## Introduction
This repository contains the project assignment. URLs given to use in the project:

* https://yts.mx/api/v2/list_movies.json - working
* https://yts.mx/api/v2/movie_details.json - working
* https://yts.mx/api/v2/movie_comments.json - not working (asked via email but no response - so I have to skip this step)
* https://yts.mx/api/v2/movie_suggestions.json - working

See [Postman Collection](https://github.com/hamza-faroooq/SwiftyMovies/blob/main/YTS%20APIS.postman_collection.json.zip) for more details.
Icons are taken from [Icons8](https://icons8.com).

## Tools and Usage
The current supported iOS verions are v14.5 and above. Xcode version used for this project is v12.5. Download the repo and install pods if necessary.

## Core Functionality
This is a movies app where user can see list of available movies, can search throught the list, can see movie details and can download the movie.

## Explanation

### Home Screen List View
This is the screen where user landed for the first time. Here user can see a list of available movies. Can Search through them and see a little bit of the details as well.

![](Screenshots/HomeListView.png)

### Home Screen Grid View
The user can also see the movies in grid view. Just click on the top right button and the display will change.

![](Screenshots/HomeGridView.png)

### Home Screen Search
As the user starts typing the title of the movie, the display of the app starts updating immediately depending upon the words used by the user.

![](Screenshots/HomeSearch.png)

### Movie Detail Screen
Next is the movie details screen where user can see movie description in more detail.

![](Screenshots/MovieDetail.png)

### Movie Detail Screen - Suggessions
Also the user can also the more movie suggession at the last part of the movie detail screen.

![](Screenshots/MovieSuggession.png)

User can also download the movie by clicking on the download button in the movie detail screen. And in the end, the user can also view suggessted movie detail by clicking on any of the item available.

## Auther
Hamza Farooq, hamza_faroooq@yahoo.com
