# SA:MP Server Status Discord Bot

A premium Discord bot for monitoring San Andreas Multiplayer (SA-MP) servers. It features real-time status updates, player counts, uptime tracking, and interactive buttons.

## ✨ Features
- **Real-time Status**: Updates automatically every 30 seconds.
- **Detailed Stats**: Shows players, gamemode, map, uptime, and restart history.
- **Outage Tracking**: Keeps track of server downtime.
- **Interactive UI**: "Copy IP" and "Refresh" buttons for ease of use.
- **Presence**: Bot status shows current player count.

## 🚀 Getting Started

### 1. Prerequisites
- [Node.js](https://nodejs.org/) installed on your machine.
- A Discord Bot Token (Get one from [Discord Developer Portal](https://discord.com/developers/applications)).
- The ID of the channel where the bot will post the status.

### 2. Configuration
1. Open the `.env` file and replace `YOUR_DISCORD_TOKEN_HERE` with your actual bot token.
2. Open the `config.json` file to customize:
   - `host`: Your SA-MP server IP.
   - `port`: Your SA-MP server port (default: 7777 or 7785).
   - `statusChannelId`: The ID of the Discord channel for updates.
   - `serverName`: Your server's display name.
   - `bannerURL`: Link to your server's banner image.

### 3. Installation & Run
1. Open your terminal in this folder.
2. Run `npm install` (already done if you are using my generated project).
3. Run `npm start` to launch the bot.

## 🛠️ Files Overview
- `index.js`: Main bot logic and status update loop.
- `config.json`: Server and appearance settings.
- `stats.json`: Persistent data for outages and uptime.
- `.env`: Secret credentials (bot token).

## 💡 Support
If you want to add more features like **RCON commands**, **Custom Emojis**, or **Advanced Player Stats**, feel free to ask me for more refinements!

*Tip: To get a channel ID, enable Developer Mode in Discord Settings > Advanced, then right-click a channel and select "Copy Channel ID".*
