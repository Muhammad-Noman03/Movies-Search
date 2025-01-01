# Movies Search App

This is a Movies Search App built with React and Vite. The app allows users to search for movies and add them to their favorites list. The app uses The Movie Database (TMDb) API to fetch movie data.

## Features

- Search for movies
- View popular movies
- Add movies to favorites
- Remove movies from favorites
- Persist favorites in local storage

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Muhammad-Noman03/Movies-Search.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Movies-Search
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Usage

1. Start the development server:
   ```sh
   npm run dev
   ```
2. Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

## Project Structure

- `src/App.jsx` - Main application component
- `src/components` - Contains reusable components like MovieCard and NavBar
- `src/contexts` - Contains the MovieContext for managing movie-related state
- `src/css` - Contains CSS files for styling the app
- `src/pages` - Contains page components like Home and Favorites
- `src/services` - Contains API service functions for fetching movie data

## API

The app uses The Movie Database (TMDb) API to fetch movie data. You can find the API key and base URL in `src/services/api.js`.

## Dependencies

The app has the following dependencies as listed in `package.json`:

- `react`: ^18.3.1
- `react-dom`: ^18.3.1
- `react-router-dom`: ^6.28.0

## Dev Dependencies

- `@eslint/js`: ^9.13.0
- `@types/react`: ^18.3.12
- `@types/react-dom`: ^18.3.1
- `@vitejs/plugin-react`: ^4.3.3
- `eslint`: ^9.13.0
- `eslint-plugin-react`: ^7.37.2
- `eslint-plugin-react-hooks`: ^5.0.0
- `eslint-plugin-react-refresh`: ^0.4.14
- `globals`: ^15.11.0
- `vite`: ^5.4.10

## Running the App

To run the app, use the following commands:

- Start the development server:
  ```sh
  npm run dev
  ```
- Build the app for production:
  ```sh
  npm run build
  ```
- Preview the production build:
  ```sh
  npm run preview
  ```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Reporting Issues

If you encounter any issues or have feature requests, please open an issue in the [GitHub repository](https://github.com/Muhammad-Noman03/Movies-Search/issues).

## License

This project is licensed under the MIT License.
