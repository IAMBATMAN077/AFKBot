<!-- Last updated: 2025-08-21T17:25:27Z -->
# 🤖 Minecraft AFK Bot (Mineflayer-Based)
## ⚡ Installation

### 1. Clone the repository

```bash
git clone https://github.com/nuekkis/Minecraft-AFK-Bot.git
cd Minecraft-AFK-Bot
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure `config.json`

```json
{
  "serverHost": "yourserver.aternos.me",
  "serverPort": 25565,
  "botUsername": "MyBotName",
  "botChunk": 4
}
```

> ⚠️ Make sure the server is in offline mode if you're not using premium accounts.

---

## 🤖 Starting the Bot

```bash
node bot.js
```

On successful connection:

* You'll see `✅ BotName is Ready!` in the console
* After 5 seconds, all loaded chunks are cleared
* Every 20 seconds, any chunks beyond a 6-chunk radius will be removed
