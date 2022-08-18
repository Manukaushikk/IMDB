# IMDB App Link
https://imdb-b4c35.web.app



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

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




 
