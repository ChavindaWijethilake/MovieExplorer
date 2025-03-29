# Movie Explorer

A React-based Movie Explorer application that allows users to browse and search for movies using **TMDB API**. This project is built using **React**, **Tailwind CSS**, and **Appwrite** as the backend for authentication and data storage. It covers the fundamentals of React, making it a great learning project for beginners.

## Features
- Browse trending movies
- Search for movies by title
- View detailed movie information
- User authentication with Appwrite
- Responsive UI with Tailwind CSS

## Tech Stack
- **React** - Frontend framework
- **Tailwind CSS** - Styling
- **Appwrite** - Backend services (Authentication & Database)
- **TMDB API** - Movie data source

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/movie-explorer.git
   cd movie-explorer
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following:
   ```sh
   REACT_APP_TMDB_API_KEY=your_tmdb_api_key
   REACT_APP_APPWRITE_PROJECT_ID=your_appwrite_project_id
   REACT_APP_APPWRITE_ENDPOINT=your_appwrite_endpoint
   ```

4. **Run the app:**
   ```sh
   npm start
   ```

## Usage
- Search for movies using the search bar.
- Click on a movie card to view details.
- Sign up/sign in to save favorite movies (if implemented).

## Deployment
You can deploy this app using platforms like **Vercel**, **Netlify**, or **Firebase Hosting**.

## Learnings
This project covers key **React fundamentals**, including:
- React functional components & hooks
- State management with `useState` & `useEffect`
- API calls using `fetch`
- Routing with `react-router-dom`
- Authentication & database integration with Appwrite

## Contributing
Feel free to fork the repository and open a pull request with improvements.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [TMDB API](https://www.themoviedb.org/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Appwrite](https://appwrite.io/)
