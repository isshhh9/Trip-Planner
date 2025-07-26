# 🧭 Trip-Planner

The **AI-Powered Trip Planner App** is a full-stack web application designed to simplify and enhance the travel planning experience. With the help of **Gemini AI**, users can generate personalized trip itineraries based on their preferences, location, and travel dates. The app also integrates **Google Authentication** and the **Google Places API** to provide rich details and imagery. Whether you're a solo traveler or planning a family vacation, this app makes intelligent travel planning seamless, beautiful, and interactive.

## ✨ Features

* **AI-Generated Itineraries**
  Generate personalized travel plans using Gemini AI, tailored to your preferences, destination, and duration.

* **Intuitive Trip Form**
  A clean and simple interface that collects key trip details like destination, travel dates, interests, and more.

* **Secure Google Sign-In**
  Users can log in easily and safely using their Google accounts through Firebase Authentication.

* **Save and Revisit Trips**
  Planned trips are automatically saved to Firestore, so users can come back and view them anytime.

* **Location-Based Images**
  Enhance the travel experience with photos of destinations fetched dynamically using the Google Places and Photos APIs.

* **Trip History Dashboard**
  Each user has access to a personalized dashboard where they can view and manage their previously created itineraries.

* **Responsive and Modern Design**
  Built with TailwindCSS, the app adapts to all screen sizes, ensuring a seamless experience across devices.

* **Deployed and Ready to Use**
  The app is fully deployed using Firebase Hosting and is accessible online, ready for users to plan their next adventure.

---

## 🧰 Tech Stack

### Frontend

* **React.js** – Core UI framework
* **React Router** – Client-side routing
* **TailwindCSS** – Styling and layout

### Backend / Services

* **Firebase Firestore** – Realtime NoSQL database
* **Firebase Authentication** – Secure Google Sign-In
* **Firebase Hosting** – Deployment and hosting

### AI & APIs

* **Gemini AI** – Generates travel plans with natural language prompts
* **Google Places API** – Fetches place details and metadata
* **Google Photos API** – Fetches relevant location images

---

## 📁 Project Structure

```bash
ai-trip-planner/
│
├── public/                     # Static assets and index.html
│
├── src/
│   ├── assets/                 # Custom images and icons
│   ├── components/             # Reusable React components (Header, TripCard, etc.)
│   ├── pages/                  # Individual route pages (Home, Planner, Trips, etc.)
│   ├── firebase/               # Firebase configuration and service files
│   ├── services/               # API logic for Gemini AI, Google APIs
│   ├── context/                # Auth context and other global providers
│   ├── App.jsx                 # Main app file with routing
│   ├── main.jsx                # Entry point for React
│   └── index.css               # TailwindCSS styles
```
