# 🎬 Movie Database Website

A fully functional and responsive **Movie Database Website** that allows users to search for movies, view detailed information, and explore movie categories like trending, top-rated, and more. Built using **HTML**, **CSS**, and **Vanilla JavaScript**, and powered by an external movie API like [TMDb](https://www.themoviedb.org/documentation/api) or [OMDb](https://www.omdbapi.com/).

---

## 🌟 Features

- 🔍 Search movies by title
- 📄 View detailed movie info (poster, rating, overview, genres, release date)
- 🎞️ Browse trending and top-rated movies
- 🎭 Movie cards with dynamic content
- 📁 Organized project structure with modular JavaScript files
- 📱 Responsive design with clean layout
- 🧭 Sidebar navigation and movie list pages

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- External Movie API (e.g., TMDb or OMDb)
- Responsive Web Design

---

## 📁 Folder Structure

movie-database/
├── index.html
├── movie-list.html
├── detail.html
├── assets/
│ ├── css/
│ │ └── style.css
│ ├── js/
│ │ ├── api.js
│ │ ├── detail.js
│ │ ├── global.js
│ │ ├── index.js
│ │ ├── movie-card.js
│ │ ├── movie-list.js
│ │ ├── search.js
│ │ └── sidebar.js
│ └── images/
│ └── (all image files used in project)
└── README.md

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/JashanjotSingh812/movie-database
cd movie-database
2. Get a Free API Key
Register at TMDb or OMDb

Obtain your API key

3. Configure API Key
In assets/js/api.js, replace your_api_key_here with your actual API key:

js
Copy
Edit
const API_KEY = 'your_api_key_here';
🧠 How It Works
index.html: Home page with trending movies and a search bar.

movie-list.html: Displays lists of movies by category (e.g., Top Rated, Now Playing).

detail.html: Shows detailed info about a selected movie.

api.js: Handles all API fetch requests.

movie-card.js: Dynamically generates HTML for each movie card.

global.js: Contains global constants and helper functions.

search.js: Manages search functionality and redirection.

sidebar.js: Dynamically renders sidebar links/categories.

style.css: Contains all the styles for layout and responsiveness.

📸 Screenshots
(Add screenshots or UI mockups here for better visualization)

✨ Future Enhancements
Add user login and favorites list (using localStorage or backend)

Display trailers via YouTube API

Dark/light theme toggle

Infinite scroll for movie listings

📌 Deployment
You can deploy this project on:

GitHub Pages

Netlify

Vercel

To deploy on GitHub Pages:

Push your project to GitHub

Go to Settings > Pages

Select the main branch and root folder, click Save

🙋‍♂️ Author
Developed by Jashanjot Singh
