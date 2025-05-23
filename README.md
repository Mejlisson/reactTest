<h1>
  Comic Vine – A Comic Web App
  <img src="public/readme.gif" alt="Comic Vine Icon" width="150" style="vertical-align: middle; margin-right: 10px;" />
  
</h1>


**Comic Vine** is a responsive, stylish, and interactive web application that will let users to explore and interact with comic book data such as characters, creators, movies, series, and more by allowing user  rate, and favorite comic book content ...

This project is part of my frontend development course, where I focused on **user experience**, **responsive design**, **component reuse**, and **clean architecture**. The app is styled in a **comic book art style**, inspired by vintage panels, bold frames, and vibrant colors – creating a fun and engaging experience for comic lovers.

---

## Features

-  **Search** for characters, series, issues, volume and creators using the Comic Vine API  
-  **Favorite** items and store them in `localStorage`  
-  **Rate** comics with stars, reviews, and mark them as "read"  
-  **Flip cards** reveal detailed ratings and personal notes  
-  **Responsive design** tailored for mobile and desktop  
-  **Comic-style UI** using Tailwind CSS with custom comic-themed variables  
-  **Video intro** and animated sections to enrich user experience  
-  **"Did You Know?"** fun facs **Comic Stats** from user data  
-  **Optimized** with reusable components and clean architecture  

---

## Built With

- **React** – Component-based UI  
- **TypeScript** – Type-safe development  
- **Tailwind CSS** – Utility-first styling  
- **CSS Variables** – Custom comic palette  
- **React Router** – Routing between views  
- **LocalStorage** – Save favorites and ratings  
- **Comic Vine API** – Real-time comic data  

---

## Project Structure
```text
src/
├── api/         # Handles all API fetches and utilities to Comic Vine API
├── components/  # Reusable UI components like cards, modals, buttons, layout, etc.
├── context/     # Global state management using React Context (e.g. favorites, ratings)
├── pages/       # Route-specific views (Home, Detail, Favorites, Ratings, Search, etc.)
├── types/       # TypeScript type definitions and interfaces for API responses
└── App.tsx      # Main app component including routing and layout structure

```

---

## Getting Started

### 1.Clone the repo
```https://github.com/Mejlisson/Slutprojekt-React-F24.git```
### 2. Install dependencies
```npm install```
### 3. Create a .env file and add your Comic Vine API key
```VITE_COMICVINE_API_KEY=your_api_key_here```
### 4. Start the development server
```npm run dev```

## UX Highlights
- Comic-style design with bold colors, speech bubbles, and panel layouts
- Smooth animations for flip cards, transitions, and rating modals
- Mobile-first responsive layout
- Feedback and error handling for API calls


---
