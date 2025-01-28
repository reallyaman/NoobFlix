# NoobFlix

NoobFlix is a dynamic web application that allows users to browse, search, and explore movies. It provides information such as ratings, trending movies, and more. Powered by [The Movie Database (TMDB) API](https://www.themoviedb.org/documentation/api), it ensures users have access to a wide range of movie data.

## Features

- **Search Movies:** Easily search for any movie by its title using the search functionality.
- **Trending Movies:** Discover the most popular and trending movies updated in real-time.
- **Movie Ratings:** View movie ratings, descriptions, and release dates fetched directly from the TMDB API.
- **Detailed Movie Information:** Access in-depth details such as genres, cast, crew, and runtime for each movie.
- **Responsive Design:** Optimized for all devices, ensuring a seamless user experience on desktop, tablet, and mobile.
- **Error Handling:** User-friendly error messages for scenarios such as API failures or no search results.

## Screenshots

### Home Page
![Home Page](screenshots/home-page.png)

### Search Results
![Search Results](screenshots/search-results.png)

### Movie Details
![Movie Details](screenshots/movie-details.png)

## Tech Stack

- **Frontend:** React with Vite for fast builds and optimized performance.
- **Styling:** Tailwind CSS for modern, responsive UI design.
- **API:** [TMDB API](https://www.themoviedb.org/documentation/api) for movie data.
- **State Management:** React Context API for managing global states efficiently.
- **Icons:** Lucide Icons for modern, scalable SVG icons.

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or later)
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/noobflix.git
   cd noobflix
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your TMDB API key:

   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173`.

## Deployment

To deploy the application, build the project and host it on your preferred platform (e.g., Vercel, Netlify):

1. Build the project:

   ```bash
   npm run build
   ```

2. Deploy the contents of the `dist` folder to your hosting platform.

### Suggested Platforms

- [Vercel](https://vercel.com/): Zero-configuration deployment for React apps.
- [Netlify](https://www.netlify.com/): Free hosting with CI/CD integration.

## API Usage

NoobFlix uses TMDB API for fetching movie data. You need to sign up on TMDB and generate an API key.

- [TMDB API Documentation](https://www.themoviedb.org/documentation/api)

### API Endpoints Used

- **Trending Movies:** `/trending/movie/day`
- **Search Movies:** `/search/movie`
- **Movie Details:** `/movie/{movie_id}`

## Folder Structure

```
noobflix/
├── public/             # Static assets
├── src/
│   ├── components/     # Reusable components (e.g., Header, Footer, MovieCard)
│   ├── pages/          # Application pages (e.g., Home, Search, MovieDetails)
│   ├── utils/          # Utility functions (e.g., API calls, helper functions)
│   ├── context/        # Global state management (e.g., search context)
│   ├── styles/         # Global styles and theme settings
│   ├── App.jsx         # Root component
│   └── main.jsx        # Application entry point
├── .env                # Environment variables
├── package.json        # Project metadata and scripts
└── README.md           # Project documentation
```

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [The Movie Database (TMDB)](https://www.themoviedb.org/)
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)

## Future Enhancements

- **User Authentication:** Allow users to create accounts, log in, and save their favorite movies.
- **Recommendations:** Provide personalized movie recommendations based on user preferences.
- **Dark Mode:** Add a toggle for dark and light themes.
- **Enhanced Search:** Include filters for genres, release year, and ratings.
- **Pagination:** Improve the search results page with proper pagination.

---

Feel free to enhance this README by adding more details, like demo links, specific technologies used, or customization instructions.

