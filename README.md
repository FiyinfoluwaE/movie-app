# 🎥 Movie Search App

A simple, responsive movie search application built with **React**, **Tailwind CSS**, **Axios**, and **Appwrite**. Users can search for movies via The Movie Database (TMDb) API and view trending movies based on the number of times a movie was searched.

---

## 🚀 Features

- 🔍 Search movies by title
- 📊 Track and display trending search terms
- 💅 Built with Tailwind CSS for styling
- ⚡ Debounced search to reduce API calls
- 🧠 State management with React Hooks
- 🔐 Environment variables using Vite
- ☁️ Appwrite used to store and track search history

---

## 🧪 Tech Stack

- React
- Vite
- Tailwind CSS
- Axios
- Appwrite
- TMDb API

---

## 🔧 Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/movie-search-app.git
   cd movie-search-app
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root with the following:

   ```env
   VITE_API_KEY=your_tmdb_api_key
   VITE_APPWRITE_PROJECT_ID=your_project_id
   VITE_APPWRITE_DATABASE_ID=your_database_id
   VITE_APPWRITE_COLLECTION_ID=your_collection_id
   ```

4. **Start the development server**

   ```bash
   npm run dev
   ```

---

## 🧰 Environment Variables

Ensure all `.env` variables **start with `VITE_`** for Vite to read them.

| Variable                      | Description                         |
| ----------------------------- | ----------------------------------- |
| `VITE_API_KEY`                | Your TMDb API key                   |
| `VITE_APPWRITE_PROJECT_ID`    | Appwrite project ID                 |
| `VITE_APPWRITE_DATABASE_ID`   | Appwrite database ID                |
| `VITE_APPWRITE_COLLECTION_ID` | Appwrite collection for search logs |

---

## 🙌 Acknowledgments

- [TMDb API](https://www.themoviedb.org/documentation/api)
- [Appwrite](https://appwrite.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React](https://reactjs.org/)
