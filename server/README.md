# 🚀 AI Fitness Tracker Backend

This is the backend API for the AI Fitness Tracker application.

It is built using **Strapi** and provides APIs for authentication, food logs, activity logs, user profiles, and AI-powered food image analysis using Google Gemini.

---

## 🛠️ Tech Stack

- Strapi CMS
- Node.js
- TypeScript
- PostgreSQL (Neon)
- Google Gemini API

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/bhargavguthi/Fitness_Tracker.git
```

Go to the server folder:

```bash
cd server
```

Install dependencies:

```bash
npm install
```

---

## ▶️ Run the Server

Development mode:

```bash
npm run develop
```

Production mode:

```bash
npm run start
```

Build the admin panel:

```bash
npm run build
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

> **Important:** Never commit your real API keys or secrets to GitHub.

---

## 📌 Features

- User Authentication
- Food Log API
- Activity Log API
- AI Food Image Analysis
- PostgreSQL Database
- REST API

---

## 👨‍💻 Author

**Guthi Srinivasa Bhargav**

GitHub: https://github.com/bhargavguthi