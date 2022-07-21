# Queue Bot
A simple bot for managing a queue of users in Discord.

## Installation
These instructions assume you have already created an application from within the [Discord Developer Portal](https://discord.com/developers/applications), registered it as a bot, and invited it to your Discord server.
1. Type `npm install queue-bot` in your terminal
2. Open the `config.json` file and add your bot's token to the `token` field
3. Run the bot by typing `npm start`

## Usage
Once the bot is running, start a queue by issuing the `!queue start` command.
### Queue Commands
| Command | Description |
| --------------- | --------------- |
| `!q start` | Start a queue (Admins-only) |
| `!q add @username` | Add a user to the queue (Admins-only) |
| `!q remove @username` | Remove a user from the queue (Admins-only) |
| `!q join` | Join the queue |
| `!q leave` | Leave the queue |
| `!q time` | See how long you've been in the queue |



Credits:binlabs
