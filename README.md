# Movies2Watch

Movies2Watch is a web application that allows users to discover and search for movies using The Movie Database (TMDb) API. The application displays the most popular movies on the home page and provides a search functionality for users to find specific movies.

## Features

- **Home Page with Popular Movies**: Displays a list of the most popular movies fetched from TMDb.
- **Search Functionality**: Allows users to search for specific movies using the search bar.
- **Responsive Design**: Ensures a good user experience across different devices and screen sizes.

## Technologies Used

- HTML
- CSS
- JavaScript
- [The Movie Database (TMDb) API](https://www.themoviedb.org/documentation/api)

## How It Works

1. **Initial Load**:
   - On loading the app, the `returnMovies` function is called with `APILINK` to fetch and display the most popular movies.

2. **Search Functionality**:
   - When a user submits the search form, an event listener prevents the default form submission behavior.
   - The `returnMovies` function is called with the search API URL concatenated with the user's query.
   - The main content section is cleared, and the search results are dynamically displayed.

## Project Structure

### index.html

The main HTML file that defines the structure of the application, including the navigation bar, search form, and main content section.

### style.css

The CSS file that provides the styling for the application, ensuring a visually appealing and cohesive design.

### script.js

The JavaScript file that handles fetching data from TMDb, dynamically creating and inserting HTML elements to display movie data, and managing search functionality.


