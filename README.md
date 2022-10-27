# IMDB App Link
https://imdb-b4c35.web.app

# Movies App
* Used React and tailwind ,TMDB API to implement  imdb clone. 
* It contains features like searching,sorting ,pagination, bookmarks.
* Local storage was used to sync data across multiple plages
* React router DOM was used to perform navigation

### Notes How to Make
# movies
## Movies features (Product Team)
* Pages : we have Two pages 
    * Home  Page -> List of movies ✔
        * Header -> links to Movies, favourites ✔
        * banner -> First movie ka banner ✔
        * List of trending movies  ✔
        * Pagination ✔
  * Favourites Page:
        * Header -> links to Movies, favourites
        * Genres list 
        * Searchbar, no of items modifier
        * Favourite movies : sorting,✔
        * deletion feature 
        * Pagination
## Technical Prerequisites (Engineering manager)
* How to make a (Ajax)request in react and render that data on ui
  * React ->life cycle methods
* Favourite page features that are highly used: 
  * Pagination,
  * group by,
  * sorting,
  * searching
* Multiple pages -> Routing 
* Practice : communication between multiple components
* Sending data from one page to another 

  ***I will not focus on ui**

### data Source 
* Trending Movies : They are sourced from TMDB api 
  * Data Availabe from TMDB API 
      * Movies Img src 
      * Movie name 
      * Genre -> Type of movie
      * Rating 
      * Popularity
  
* data file : movies.js
* get small prepend in backdrop path (normal image ): https://image.tmdb.org/t/p/w500/
* Banner image prepend : https://image.tmdb.org/t/p/original

# Genre Data 
 let genreids = {
    28: 'Action',
    12: 'Adventure',
    16: 'Animation', 35: 'Comedy', 80: 'Crime', 99: 'Documentary', 18: 'Drama', 10751: 'Family', 14: 'Fantasy', 36: 'History',
    27: 'Horror', 10402: 'Music', 9648: 'Mystery', 10749: 'Romance', 878: 'Sci-Fi', 10770: 'TV', 53: 'Thriller', 10752: 'War', 37: 'Western'
  }

# Pending Topics
  * sort by popularity ✔
  * Searching ✔
  * Pagination ✔
  * Sending message from movies to favourite to movies -> like dislike(movies page) ,  localstorage
  * Group by Genre  
  * Deletion of movies in favourites -> delete (fav), skip?? 
  * Deployment on firebase 
** share it's code -> mon : 5 to 7 tailwind 
** Pending : Styling  

## HOSTING 
* npm run build
* go to firebase console
* create project  -> put the name -> don't add analytics
* go to cmd -> npm i -g firebase-tools 
* firebase login -> browser will open -> login
* firebase init
* proceed -> y
* option -> hosting -> space  then enter
* existing -> choose -=> space press then
* spa-> y
* rewrite-> n
* firebase deploy

### if you do change -> build
* npm run build
* firebase init
* proceed -> y
* option -> hosting -> space  then enter
* existing -> choose -=> space press then
* spa-> y
* rewrite-> n
* firebase deploy




## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)




 
