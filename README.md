# 🎬 CiniSphere — AI-Powered Movie Discovery & Social Platform

**Discover movies. Get personalized recommendations. Connect with movie lovers.**

🔗 **Live Demo:** [Explore CiniSphere](https://cinisphere-app.vercel.app/)

CiniSphere is a full-stack movie discovery and social networking platform that combines AI-powered movie recommendations with an interactive community experience. Users can explore movies, discover films based on their mood and preferences, manage watchlists, share posts, join communities, and chat with other movie enthusiasts.

## 📌 Project Overview

CiniSphere consists of three main components:

- **`frontend/`** — React and TypeScript single-page application.
- **`backend/`** — FastAPI backend server built with Python.
- **`ml_engine/`** — Machine learning models and movie recommendation logic.

## ✨ Features

- 🎥 **Movie Discovery:** Browse and explore movies.
- 🤖 **AI-Powered Recommendations:** Discover movies using content-based and hybrid recommendation techniques.
- 🎭 **Mood-Based Recommendations:** Find movies based on mood, language, genre, and personal preferences.
- 📋 **Watchlists:** Save movies to watch later.
- 👤 **User Profiles:** Create profiles and connect with other users.
- 💬 **Real-Time Chat:** Communicate through direct and community chats.
- 🌐 **Movie Communities:** Join communities and interact with movie fans.
- 📝 **Social Posts:** Share movie opinions and recommendations.
- 🔔 **Notifications:** Stay updated on relevant activities.
- 🛡️ **Authentication and Moderation:** Support user access and community management.

## 🛠️ Tech Stack

### Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- React Router

### Backend

- Python
- FastAPI
- REST APIs
- JWT Authentication
- WebSockets

### Databases

- **MongoDB:** Movie and recommendation data.
- **PostgreSQL:** Relational and social data.

### Machine Learning

- Python
- Scikit-learn
- TF-IDF Vectorization
- Cosine Similarity
- Hybrid Recommendation System

## 🧠 Recommendation System

CiniSphere uses machine learning techniques to improve movie discovery.

1. **Data Processing:** Prepare movie metadata for recommendation.
2. **Feature Extraction:** Convert movie metadata into numerical vectors using TF-IDF.
3. **Similarity Calculation:** Use cosine similarity to identify movies with similar characteristics.
4. **Hybrid Ranking:** Combine content similarity with popularity and freshness.
5. **Personalization:** Use user preferences to tailor recommendations.
6. **Diversity Reranking:** Improve variety in the recommended results.

## 🏗️ Project Structure

```text
cinisphere/
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
├── backend/
│   ├── main.py
│   └── requirements.txt
├── ml_engine/
├── .gitignore
└── README.md
```

_Note: This is an illustrative structure. Actual file names and folders may differ._

## 🚀 Getting Started

### Prerequisites

- Node.js and npm
- Python 3.10+
- MongoDB
- PostgreSQL

### 1. Clone the Repository

```bash
git clone https://github.com/Kishanamz/cinisphere-app.git
cd cinisphere-app
```

### 2. Set Up the Backend

```bash
cd backend
python -m venv .venv
```

Activate the virtual environment on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

Install the backend dependencies:

```bash
pip install -r requirements.txt
```

Configure your required environment variables before starting the backend.

### 3. Set Up the Frontend

Open a new terminal from the project root:

```bash
cd frontend
npm install
npm run dev
```

Open the local URL displayed in your terminal.

### 4. Configure the Database

Configure the MongoDB and PostgreSQL connection strings required by your application. Ensure the database services are available before running the backend.

## 🔐 Environment Variables

Create a local `.env` file for the required configuration, which may include:

- Database connection strings.
- JWT secret.
- Movie API key.
- Frontend and backend URLs.

**Security:** Never commit passwords, API keys, JWT secrets, or production credentials to GitHub. Use placeholder values in any `.env.example` file.

## 🎯 Project Objectives

- Improve movie discovery through personalized recommendations.
- Apply machine learning techniques to movie metadata.
- Combine movie discovery with social networking features.
- Create an engaging platform for movie enthusiasts.
- Explore the integration of AI, full-stack development, and real-time communication.

## 🔮 Future Enhancements

- Improved collaborative filtering.
- More advanced recommendation models.
- Enhanced personalization based on viewing history.
- Movie analytics and user insights.
- Further performance and deployment improvements.

## 👨‍💻 Author

**Kishan G**

B.Tech — Artificial Intelligence and Data Science

Interests: Machine Learning, Data Analytics, and Full-Stack Development.

---

⭐ If you find CiniSphere interesting, consider starring the repository!

🔗 **Live Application:** [https://cinisphere-app.vercel.app/](https://cinisphere-app.vercel.app/)

💻 **GitHub Repository:** [https://github.com/Kishanamz/cinisphere-app](https://github.com/Kishanamz/cinisphere-app)
