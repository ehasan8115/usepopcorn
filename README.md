# usePopcorn - A Movie Tracker App

### [Live Site](https://usepopcorn-reactjs.netlify.app/)

![usePopcorn](https://github.com/ehasan8115/Secrets-Authentication/blob/master/public/images/secrets-home.png?raw=true)

## Overview

usePopcorn is a React-based web application that allows users to search for movies, view movie details, and keep track of the movies they've watched. Users can search for movies by entering keywords, view a list of matching movies, and select a movie to see its details. They can also add movies to their "watched" list and remove them as needed.

## Features

- **Movie Search**: Users can enter search queries to find movies matching their keywords.
- **Movie List**: Displays a list of movies based on the search query.
- **Movie Details**: Users can click on a movie in the list to view detailed information about it.
- **Watched List**: Allows users to keep track of the movies they've watched.
- **LocalStorage**: Watched movies are stored locally, so they persist between sessions.
- **Error Handling**: Provides error messages if there are issues with the movie search.

## Technologies Used

- React: The app is built using the React library for building user interfaces.
- React Hooks: Various hooks such as `useState`, `useEffect`, and custom hooks are used to manage state and side effects.
- LocalStorage: The `useLocalStorageState` hook is used to store watched movies in the browser's Local Storage.
- Custom Hooks: Custom hooks like `useKey` and `useMovies` are used for specific functionalities.
- [OMDb API](https://www.omdbapi.com/): The Open Movie Database API is used for fetching movie data.

## Installation

To run the Movie Tracker App locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Install dependencies using `npm install` or `yarn install`.
4. Create a `.env` file in the project root directory and add your OMDb API key as follows:
