# 🔍 GitHub Profile Finder

[![GitHub API](https://img.shields.io/badge/API-GitHub-lightgrey.svg)](https://docs.github.com/en/rest)
[![Tailwind CSS](https://img.shields.io/badge/CSS-Tailwind_4.0-blue.svg)](https://tailwindcss.com/)
[![JS ES6+](https://img.shields.io/badge/JS-ES6%2B-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A sleek and responsive web application that allows users to search for any GitHub profile and instantly view their bio, location, followers, following, and repository statistics.

---

## ✨ Features

- **Real-time Search:** Fetches user data directly from the official GitHub REST API.
- **Dynamic UI Injection:** Uses JavaScript to dynamically update the DOM without page reloads.
- **Modern Styling:** Built with **Tailwind CSS 4.0** for a mobile-first, dark-themed professional look.
- **Error Handling:** Basic validation to handle invalid usernames or empty searches.
- **Date Formatting:** Automatically parses and cleans the GitHub "Joined" date into a readable format.

---

## 🛠️ Technical Implementation

### **Core Logic**
The application uses the `fetch()` API with async patterns to communicate with:
- `https://api.github.com/users/{username}`

### **Code Highlights**
- **Form Submission:** Prevented default browser behavior to ensure a smooth Single Page Application (SPA) experience.
- **Conditionals:** Handled null values for Bio, Location, and Company fields to ensure the UI never looks broken (e.g., displaying "Anywhere on Earth" if location is missing).

---

## 🚀 How to Use

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/PuneetVerma07/GithubProfileChecker.git](https://github.com/PuneetVerma07/GithubProfileChecker.git)

2. **Open the Project:**
    Simply open index.html in any modern web browser.

3. **Search:**
   Type any GitHub username (like PuneetVerma07) and hit "Search".

## UI Preview

The app features a card-based layout with:
-> Circular Avatar with glow effects.
-> Stat Grid for quick repo and follower counts.
-> Dark mode optimized for developer eyes.
