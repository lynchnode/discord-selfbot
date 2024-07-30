# discord-selfbot

Feel free donate to my EVM address

```
0x03974DdCA9eE8a606287c361AE37e2b78F53CB3a
```

This project contains two Discord self-bots:
1. **Auto Chat Delete Bot** (`autoChatDel.js`): Automatically sends messages to a specified channel and deletes them after a specified time.
2. **Auto Chat Save Bot** (`autoChatSave.js`): Automatically sends messages to a specified channel and keeps them.

## Requirements

- [Node.js](https://nodejs.org/) installed
- A Discord account
- Your Discord Token and the Channel ID where you want to send messages

## Steps

### 1. Clone the repository

```
git clone https://github.com/sekuja/discord-selfbot.git
cd discord-selfbot
```

### 2. Install dependencies

```
npm install
```

### 3. Create a `.env` file

Create a `.env` file in the project directory and add your Discord Token and the Channel ID:

```
DISCORD_TOKEN=your_discord_token_here
CHANNEL_ID=your_channel_id_here
```

## Usage

### Running the Auto Chat Delete Bot

This bot sends messages to the specified channel and deletes them after a short delay.

```
npm run start:autoChatDel
```

### Running the Auto Chat Save Bot

This bot sends messages to the specified channel and keeps them.

```
npm run start:autoChatSave
```

## Code Overview

`autoChatDel.js`
This script sends a message to a specified Discord channel every 15 seconds and deletes it after 10 seconds
