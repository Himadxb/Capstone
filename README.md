# 🚀 CodeQuest – Gamified Python Learning Platform

CodeQuest is a web-based platform that teaches Python programming through interactive challenges, quizzes, and real-time feedback. Developed as a capstone project at Curtin University Dubai, it emphasizes a fun, engaging, and progressive learning journey for beginners.

---

## 📚 Features

- 🧠 Python coding challenges with live execution via Judge0 API  
- 🔐 Role-based login and user authentication with Firebase  
- ⚡ Real-time XP, progress, and badge tracking  
- 🏆 Gamification through levels, badges, and final boss challenge  
- 📊 Leaderboard to encourage healthy competition  
- 🎯 Adaptive feedback based on user performance  

---

## 🛠️ Tech Stack

| Layer           | Technology                        |
|------------------|------------------------------------|
| Frontend         | React, Redux, Vite                 |
| Backend          | Node.js, Express                   |
| Database         | Firebase Firestore                 |
| Authentication   | Firebase Auth                      |
| Code Execution   | Judge0 API                         |
| CI/CD            | GitHub Actions + Firebase Hosting  |

---

## 📁 Project Structure

```plaintext
codequest/
├── client/                 # React frontend
│   ├── components/         # Reusable UI elements (XPBar, Editor, etc.)
│   ├── pages/              # Route-based views (Dashboard, Quiz)
│   ├── redux/              # Global state (XP, Auth, Badges)
│   └── assets/             # Static resources
├── server/                 # Node.js backend
│   ├── routes/             # API routes (auth, submit, leaderboard)
│   ├── middleware/         # JWT checks, validation
│   └── services/           # Firestore & Judge0 logic
├── .github/workflows/      # GitHub Actions workflows
├── .firebaserc             # Firebase project info
├── firebase.json           # Hosting config
├── .env.example            # Example env variables
└── README.md               # Project overview
```

---

## ✨ Acknowledgments

Capstone project submitted to Curtin University Dubai.  
Special thanks to our supervisor and teammates for their contributions.
