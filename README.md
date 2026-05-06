# Bale-EscapeRoom-Bot
A Python-based interactive chatbot designed for Bale Messenger to facilitate an automated Escape Room experience. It manages puzzles, handles user progress, and provides a dynamic storytelling interface.
# Bale Escape Room Bot 🧩

An interactive, story-driven bot built with **Python** specifically for the **Bale Messenger** platform. This project aims to digitize the Escape Room experience, allowing users to solve mysteries, interact with virtual objects, and progress through a narrative directly within their chat environment.

## 🚀 Features
- **State Management:** Tracks user progress through different "rooms" and story stages.
- **Dynamic Puzzles:** Supports text-based, logic, and multimedia puzzles.
- **Interactive Components:** Utilizes Bale's keyboard and button features for seamless navigation.
- **Hint System:** An integrated system to provide clues if users get stuck.
- **Asynchronous Handling:** Built using asynchronous Python libraries for high performance and responsiveness.

## 🛠 Tech Stack
- **Language:** Python 3.9+
- **API Wrapper:** [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) (Compatible with Bale Bot API) or specific Bale SDKs.
- **Database:** SQLite/PostgreSQL (for saving user states and scores).
- **Environment:** Dockerized for easy deployment.

## 📂 Project Structure
```text
├── src/
│   ├── main.py          # Entry point of the bot
│   ├── handlers/        # Command and message handlers
│   ├── engine/          # Game logic and state machine
│   └── database/        # DB models and connection
├── assets/              # Story images and files
├── config.py            # API tokens and configurations
└── requirements.txt     # Project dependencies

## 🎮 How to Play
coming soon...
