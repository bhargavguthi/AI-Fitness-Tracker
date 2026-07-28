# 🏋️ AI Fitness Tracker

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite)
![Strapi](https://img.shields.io/badge/Strapi-8E75FF?logo=strapi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?logo=google)

An AI-powered fitness tracking web application that helps users monitor their daily food intake, physical activities, and calorie consumption. It also uses **Google Gemini AI** to analyze food images and estimate calories.

---

## 📚 Table of Contents

- [Live Demo](#-live-demo)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Environment Variables](#-environment-variables)
- [AI Food Snap](#-ai-food-snap)
- [Deployment](#-deployment)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [Author](#-author)
- [Support](#-support)

---

## 🚀 Live Demo

**Frontend:**  
https://fitness-tracker-k8x3.vercel.app

**Backend API:**  
https://fitness-tracker-server-g1tq.onrender.com

---

## 📌 Features

- 🔐 User Authentication (Register & Login)
- 🍽️ Food Log Management
- 🏃 Activity Log Management
- 🤖 AI Food Recognition using Google Gemini AI
- 🔥 Automatic Calorie Estimation
- 📊 Daily Fitness Tracking
- ☁️ PostgreSQL Cloud Database
- 📱 Responsive User Interface
- ⚡ Fast Performance

---

## 🖼️ Screenshots

### Login

![Login](screenshots/Login.png)

### Home

![Home](screenshots/Home1.png)

### Dashboard

![Dashboard](screenshots/Home2.png)

### Food Log

![Food Log](screenshots/Foodlog.png)

### Activity Log

![Activity Log](screenshots/Activitylog.png)

### AI Food Snap

![AI Food Snap](screenshots/AIFoodSnap.png)

### Profile

![Profile](screenshots/Profile.png)

---

## 🛠️ Tech Stack

### Frontend

- React.js
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Axios

### Backend

- Strapi CMS
- Node.js
- TypeScript

### Database

- PostgreSQL (Neon)

### Artificial Intelligence

- Google Gemini API

### Deployment

- Vercel
- Render
- Neon PostgreSQL

---

## 📂 Project Structure

```text
Fitness_Tracker/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── src/
│   ├── config/
│   └── package.json
│
├── screenshots/
│   ├── Login.png
│   ├── Home1.png
│   ├── Home2.png
│   ├── Foodlog.png
│   ├── Activitylog.png
│   ├── AIFoodSnap.png
│   └── Profile.png
│
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### Prerequisites

- Node.js (v18 or later)
- npm

Clone the repository:

```bash
git clone https://github.com/bhargavguthi/Fitness_Tracker.git
```

Navigate to the project folder:

```bash
cd Fitness_Tracker
```

### Run the Frontend

```bash
cd client
npm install
npm run dev
```

### Run the Backend

```bash
cd ../server
npm install
npm run develop
```

---

## 🔑 Environment Variables

Create a `.env` file inside the `server` folder.

```env
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
ADMIN_JWT_SECRET=your_admin_jwt_secret
API_TOKEN_SALT=your_api_token_salt
APP_KEYS=your_app_keys
GEMINI_API_KEY=your_gemini_api_key
```

> Replace the placeholder values with your own credentials. Never commit your real API keys or secrets to GitHub.

---

## 🤖 AI Food Snap

1. Upload a food image.
2. Google Gemini AI analyzes the image.
3. Estimated calories are generated.
4. Save the food directly into your Food Log.

---

## 🚀 Deployment

| Service | Platform |
|---------|----------|
| Frontend | Vercel |
| Backend | Render |
| Database | Neon PostgreSQL |
| AI | Google Gemini API |

---

## 🎯 Future Improvements

- 🥗 Nutrition Analysis
- 📅 Meal Planner
- 💪 Workout Recommendations
- 📈 Weekly Reports
- 🎯 Goal Tracking
- 💧 Water Intake Tracking
- 🌙 Dark Mode
- 🔔 Push Notifications

---

## 🤝 Contributing

Contributions, suggestions, and feature requests are welcome. Feel free to fork the repository and submit a pull request.

---

## 👨‍💻 Author

**Guthi Srinivasa Bhargav**

GitHub: https://github.com/bhargavguthi

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.