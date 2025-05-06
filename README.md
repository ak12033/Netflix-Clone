# 🎥 Netflix Clone 🎬

A Netflix-inspired video streaming web application built with **React**, **Vite**, **Firebase** for authentication and database, and **The Movie Database (TMDb) API** for fetching movie and video content.

## 📺 Live Demo

👉 [Check it out here!](https://netflix-clone-two-beryl-41.vercel.app)

---

## 📖 Features

- User Authentication (Signup, Login, Logout) using Firebase Auth
- Browse movies fetched via TMDb API
- Watch movie trailers via embedded YouTube iframe
- Responsive, modern UI
- User data stored in Firebase Firestore
- Toast notifications for auth events
- Smooth horizontal scrollable cards for movie previews

---

## 🛠️ Tech Stack

- **React (Vite)**
- **Firebase (Auth + Firestore)**
- **TMDb API**
- **React Router**
- **React Toastify**
- **Vercel (Deployment)**

---

## Getting Started

To get started with the netflix-clone project, follow these steps:

1. Clone the repository from GitHub:

2. **Set Environment Variables**: Navigate to the `netflix clone` and add necessary environment variables. You may need to create a `.env` file and configure it with required variables:

   In the netflix-clone/.env file:

   ```
   # TMDb API Bearer Token
   VITE_TMDB_BEARER_TOKEN=your_tmdb_api_bearer_token
      
   # Firebase Config
   VITE_FIREBASE_API_KEY=your_firebase_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   VITE_FIREBASE_APP_ID=your_firebase_app_id
   ```

3. **Install Dependencies**: Install dependencies using npm or yarn:

   ```
   npm install
   ```

4. **Start the Server**:

   ```
   npm run dev
   ```
