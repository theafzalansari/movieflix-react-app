# 🎬 MovieFlix React – Modern Movie Discovery Application

MovieFlix React is a modern movie discovery web application built using **React**, **Vite**, **TMDB API**, and **Appwrite**.

The application allows users to browse trending movies, search thousands of movies in real time, and automatically tracks popular search terms using Appwrite for analytics. It features a responsive UI, optimized API requests with debounced search, and a smooth user experience.

---

## 🚀 Live Demo

👉 Coming Soon

---

## 📌 Features

* 🎬 **Browse Popular Movies**
  Discover the latest and trending movies fetched directly from TMDB.

* 🔍 **Real-Time Movie Search**
  Search thousands of movies instantly using the TMDB API.

* ⚡ **Debounced Search**
  Optimized API requests using manual debouncing to reduce unnecessary network calls and improve performance.

* 📊 **Trending Search Analytics**
  Tracks user search frequency using Appwrite Database to identify trending searches.

* 🖼️ **Beautiful Movie Cards**
  Displays movie posters, ratings, release year, and language in a clean card layout.

* ⏳ **Loading Spinner**
  Provides visual feedback while movie data is being fetched.

* 📱 **Responsive Design**
  Optimized for desktop, tablet, and mobile devices.

* ☁️ **Cloud Database Integration**
  Uses Appwrite as a backend service for storing and updating search metrics.

---

## 🛠️ Technologies Used

* React
* Vite
* JavaScript (ES6+)
* TMDB API
* Appwrite
* CSS3

---

## 📂 Project Structure

```text
movieflix-react/
│
├── public/
├── src/
│   ├── components/
│   │   ├── MovieCard.jsx
│   │   ├── Search.jsx
│   │   └── Spinner.jsx
│   │
│   ├── App.jsx
│   ├── appwrite.js
│   ├── index.css
│   └── main.jsx
│
├── .env.local
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env.local` file in the project root and add:

```env
VITE_TMDB_API_KEY=YOUR_TMDB_API_KEY

VITE_APPWRITE_PROJECT_ID=YOUR_PROJECT_ID
VITE_APPWRITE_DATABASE_ID=YOUR_DATABASE_ID
VITE_APPWRITE_COLLECTION_ID=YOUR_COLLECTION_ID
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/theafzalansari/moviesflix-react.git
```

Navigate to the project

```bash
cd moviesflix-react
```

Install dependencies

```bash
npm install
```

Start the development server

```bash
npm run dev
```

---

## 🎯 What I Learned

* Building scalable React applications using functional components
* Managing state effectively with React Hooks
* Consuming REST APIs using Fetch API
* Implementing manual debouncing using `useEffect`
* Optimizing API calls for better performance
* Integrating Appwrite as a Backend-as-a-Service
* Working with environment variables securely
* Structuring React projects for maintainability
* Handling asynchronous operations and error states
* Building responsive and reusable UI components

---

## 💡 Future Improvements

* ❤️ Favorite Movies / Watchlist
* 🎭 Browse Movies by Genre
* 📄 Movie Details Page
* 🌟 Top Rated & Upcoming Movie Sections
* 🔐 User Authentication
* 🌙 Dark / Light Theme Toggle
* 📑 Infinite Scrolling / Pagination
* 🎬 Movie Trailers Integration
* 📱 Progressive Web App (PWA)

---

## 📧 Contact

* LinkedIn: https://www.linkedin.com/in/afzal-ansari-312942370
* GitHub: https://github.com/theafzalansari
* Email: [theafzalansari@gmail.com](mailto:theafzalansari@gmail.com)

---

## 👨‍💻 Author

**Afzal Ansari**

F.E. Electronics & Computer Engineering Student

Aspiring Software Development Engineer 🚀

Passionate about building responsive web applications, solving real-world problems, and continuously learning modern web technologies.

---

## ❤️ Acknowledgment

This project was built as part of my React learning journey to strengthen my understanding of API integration, state management, debouncing, and backend services using Appwrite.

Special thanks to the **JavaScript Mastery** React course for the project inspiration and learning resources.

If you found this project helpful, consider giving it a ⭐ on GitHub!
