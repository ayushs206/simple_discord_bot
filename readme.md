# 🚀 Simple Discord Bot (JavaScript)

A lightweight Discord bot built using **discord.js v14** with basic prefix commands like **ping** and an **invite button**. Clean, minimal, and easy to extend.

---

## 📦 Features
- `ping` command — replies with **Pong!**
- `invite` command — sends an invite button
- Prefix-based commands
- Status/presence on startup
- Uses `.env` for tokens
- Minimal, beginner-friendly code

---

## 📁 Project Structure
```
.
├── index.js
├── .env
├── package.json
└── README.md
```

---

## 🔧 Installation

### 1. Clone the repository
```sh
git clone https://github.com/ayushs206/simple_discord_bot.git
cd simple_discord_bot
```

### 2. Install dependencies
```sh
npm install discord.js dotenv
```

### 3. Create a `.env` file
```
BOT_TOKEN=your_bot_token_here
PREFIX=!
```

---

## ▶️ Running the Bot
```sh
node index.js
```

---

## 🧠 Commands

### Ping
```
!ping
```
Returns `Pong!`

### Invite
```
!invite
```
Sends an invite button.

---

---

## ⚠️ Notes
- Do NOT share your bot token.
- Keep your `.env` private.
- Get your token from https://discord.com/developers/applications

---

## ⭐ Contributing
Fork, improve, and submit PRs. Star ⭐ the repo if you found it useful!