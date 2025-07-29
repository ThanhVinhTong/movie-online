# 🎬 Movie Online - React Movie Search App

A modern, responsive movie search application built with React, Vite, and Tailwind CSS. Search for movies using The Movie Database (TMDB) API and track your favorite searches with Appwrite backend integration.

## 🌐 Live Demo

**Visit the deployed application:** [https://thanhvinhtong.github.io/movie-online](https://thanhvinhtong.github.io/movie-online)

Experience the full functionality of the movie search app with real-time search, trending movies, and responsive design.

## ✨ Features

- **🔍 Real-time Movie Search**: Search for movies with debounced input for optimal performance
- **📱 Responsive Design**: Beautiful UI that works on desktop and mobile devices
- **⭐ Trending Movies**: View your most searched movies based on search frequency
- **🎨 Modern UI**: Clean, modern interface with gradient text effects and smooth animations
- **⚡ Fast Performance**: Built with Vite for lightning-fast development and build times
- **📊 Search Analytics**: Track search patterns using Appwrite database integration

## 🛠️ Tech Stack

- **Frontend**: React 19, Vite
- **Styling**: Tailwind CSS 4
- **Backend**: Appwrite (Database & Analytics)
- **API**: The Movie Database (TMDB) API
- **State Management**: React Hooks
- **Utilities**: react-use for debouncing

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager
- Appwrite account and project setup
- TMDB API key

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd movie-online
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory with the following variables:
   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key_here
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173` to view the application.

## 🔧 Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `VITE_TMDB_API_KEY` | Your TMDB API key for movie data | Yes |
| `VITE_APPWRITE_PROJECT_ID` | Your Appwrite project ID | Yes |
| `VITE_APPWRITE_DATABASE_ID` | Your Appwrite database ID | Yes |
| `VITE_APPWRITE_COLLECTION_ID` | Your Appwrite collection ID | Yes |

### How to get API keys:

1. **TMDB API Key**: 
   - Visit [The Movie Database](https://www.themoviedb.org/)
   - Create an account and request an API key
   - Use the API key in your `.env` file

2. **Appwrite Setup**:
   - Create an account at [Appwrite](https://appwrite.io/)
   - Create a new project
   - Set up a database with a collection for storing search analytics
   - Use the provided IDs in your `.env` file

## 📁 Project Structure

```
movie-online/
├── public/                 # Static assets
│   ├── hero-bg.png
│   ├── hero.png
│   ├── logo.png
│   ├── no-movie.png
│   ├── search.svg
│   └── star.svg
├── src/
│   ├── components/         # React components
│   │   ├── MovieCard.jsx
│   │   ├── Search.jsx
│   │   └── Spinner.jsx
│   ├── assets/            # Additional assets
│   ├── App.jsx           # Main application component
│   ├── appwrite.js       # Appwrite integration
│   ├── main.jsx          # Application entry point
│   └── index.css         # Global styles
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 🎯 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🎨 Features in Detail

### Search Functionality
- Real-time movie search with 1-second debounce
- Displays movie posters, titles, ratings, and release dates
- Handles API errors gracefully with user-friendly messages

### Trending Movies
- Shows your most frequently searched movies
- Displays top 5 trending searches based on search count
- Integrates with Appwrite for persistent data storage

### Responsive Design
- Mobile-first approach with Tailwind CSS
- Beautiful gradient effects and modern UI components
- Smooth loading states with spinner component

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Acknowledgments

- [The Movie Database](https://www.themoviedb.org/) for providing the movie API
- [Appwrite](https://appwrite.io/) for backend services
- [Vite](https://vitejs.dev/) for the build tool
- [Tailwind CSS](https://tailwindcss.com/) for styling

## Support

If you have any questions or need help with the project, please open an issue on GitHub.

---

**Happy coding! 🎬✨**
