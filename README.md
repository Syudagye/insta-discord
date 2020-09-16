# insta-discord
Basic Instagram bot that sends messages from a chat to a Discord webhook

## How to use
- Install all dependencies (`npm i`)
- Create a copy of `.env.example` to `.env` 
- Edit the following values:
	- `INSTA_USERNAME`: The bot's Instagram username
	- `INSTA_PASSWD`: The bot's Instagram password
	- `INSTA_CHAT_ID`: The Instagram Chat ID to follow (can get using web browser and DM URL) 
	- `DISCORD_WEBHOOK_URL`: The Discord Webhook URL to use
	- `DISCORD_BOT_TOKEN`: The token of the Discord bot
	- `DISCORD_CHANNEL_ID`: The Discord channel ID to use with Instagram (preferrably the same channel as the webhook) 

## Features
- [X] Send Instagram messages to Discord webhook
- [X] Send Discord messages from channel to Insta DM
- [ ] Use discord.js' built-in webhook methods
- [ ] Automatic webhook creation