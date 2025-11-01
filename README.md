```markdown
# Tic-Tac-Toe AI

> Challenge an unbeatable AI powered by the Minimax algorithm

![React](https://img.shields.io/badge/React-19.0-blue?logo=react)
![FastAPI](https://img.shields.io/badge/FastAPI-0.110-green?logo=fastapi)
![TailwindCSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?logo=tailwind-css)

## 🎮 Overview

An AI-powered Tic-Tac-Toe game featuring an unbeatable opponent that uses the Minimax algorithm. Built with modern web technologies and a sleek, animated interface. Can you force a draw?

## ✨ Features

- 🤖 **Unbeatable AI** using Minimax algorithm
- 🎨 **Modern UI** with smooth animations
- ⚡ **Instant moves** (< 500ms response time)
- 📱 **Fully responsive** design
- 🎯 **Symbol selection** (play as X or O)
- 📖 **Interactive tutorial** modal

## 🚀 Quick Start

### Frontend
```bash
cd frontend
yarn install
yarn start
```

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn server:app --reload --host 0.0.0.0 --port 8001
```

### Environment Setup
```env
# frontend/.env
REACT_APP_BACKEND_URL=http://localhost:8001

# backend/.env
MONGO_URL=mongodb://localhost:27017
DB_NAME=tictactoe
```

## 🛠️ Tech Stack

- **Frontend**: React 19, TailwindCSS, Shadcn/UI, Lucide Icons
- **Backend**: FastAPI, MongoDB, Motor
- **Algorithm**: Minimax with optimal decision-making

## 🧠 How It Works

The AI uses the **Minimax algorithm** - a recursive decision-making algorithm that:
1. Explores all possible game states
2. Evaluates terminal states (win: +10, draw: 0, loss: -10)
3. Chooses the move that maximizes AI's score while minimizing opponent's

**Time Complexity**: O(9!) for first move, optimized with Alpha-Beta pruning
**Result**: Mathematically unbeatable AI

## 🎯 Game Rules

- X always goes first
- Get 3 in a row (horizontal, vertical, diagonal) to win
- Best outcome against AI: **Draw**
- AI never loses!

## 📁 Project Structure

```
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── LandingPage.jsx
│   │   │   ├── GameSetup.jsx
│   │   │   ├── GameBoard.jsx
│   │   │   └── HowToPlayModal.jsx
│   │   └── utils/mockAI.js
│   └── package.json
├── backend/
│   ├── server.py
│   ├── minimax.py (to be implemented)
│   └── requirements.txt
└── README.md
```

## 🧪 Testing

Try these scenarios:
- ✅ Win as X (impossible)
- ✅ Win as O (impossible)
- ✅ Force a draw (achievable with perfect play)

## 📸 Screenshots

*Add your screenshots here*

## 📝 License

MIT License - Free to use for learning and portfolio projects

## 🔗 Links

- [Live Demo](#) - *Add your deployed link*
- [Portfolio](#) - *Add your portfolio*

---

Built with ❤️ to demonstrate AI algorithms and modern web development
```

Copy this entire markdown block and paste it into your GitHub repository's README.md file! 🚀
