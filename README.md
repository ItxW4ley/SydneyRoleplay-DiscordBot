# 🌆 Sydney Roleplay Bot

## 📖 Overview
Sydney Roleplay Bot is a custom-built Discord bot designed to enhance the roleplay experience with advanced moderation, utility, and community tools.



## ⚙️ Setup Instructions

### 1. Prerequisites
- [Node.js](https://nodejs.org/) v16 or higher
- [npm](https://www.npmjs.com/) (comes with Node.js)
- A Discord Bot Token (create one at the [Discord Developer Portal](https://discord.com/developers/applications))

---

### 2. Clone the Repository
```bash
git clone https://github.com/YourUsername/sydney-roleplay-bot.git
cd sydney-roleplay-bot
````


### 3. Install Dependencies

```bash
npm install
```



### 4. Configure Environment

Create a `.env` file in the root directory and add your bot token:

```env
# ==============================
# Sydney Roleplay Bot - .env
# ==============================

# Discord Configuration
DISCORD_TOKEN=your-bot-token-here
CLIENT_ID=your-discord-client-id
GUILD_ID=your-discord-guild-id
PREFIX=!

# Appearance
EMBED_COLOR=#00AEEF
SUCCESS_EMBED_COLOR=#00FF7F
ERROR_EMBED_COLOR=#FF4444

# Roles & Permissions
OWNER_ROLE_ID=123456789012345678
STAFF_ROLE_ID=123456789012345678
MOD_ROLE_ID=123456789012345678
SUPPORT_ROLE_ID=123456789012345678

# Logging Channels
LOG_CHANNEL_ID=123456789012345678
ERROR_LOG_CHANNEL_ID=123456789012345678
MOD_LOG_CHANNEL_ID=123456789012345678
JOIN_LEAVE_CHANNEL_ID=123456789012345678

# Database (MySQL Example)
DB_HOST=localhost
DB_USER=db_user
DB_PASS=db_password
DB_NAME=sydney_roleplay

# Optional Features
WELCOME_MESSAGES=true
WELCOME_CHANNEL_ID=123456789012345678
WELCOME_MESSAGE=<:SydneyRoleplay:1403710021484806315> `-` Welcome ${user}, To Sydney Roleplay You Are Member `${servermemberCount}`!

GOODBYE_MESSAGES=true
GOODBYE_CHANNEL_ID=123456789012345678
GOODBYE_MESSAGE=Goodbye {user}, we hope to see you again!

# API Keys (Optional)
OPENAI_API_KEY=your-openai-api-key
WEATHER_API_KEY=your-weather-api-key
TRANSLATE_API_KEY=your-translate-api-key

# Server Config
PORT=3000
DEBUG=false

```


### 5. Run the Bot

Start the bot with:

```bash
node srp.js
```

## ✅ Confirmation

If setup is correct, the console will show a success message and the bot will appear online in your Discord server.


