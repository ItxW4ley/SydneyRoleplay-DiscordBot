# Sydney Roleplay Bot
-------------------

Overview:
Sydney Roleplay Bot is a custom-built Discord bot designed to enhance the roleplay experience with advanced moderation, utility, and community tools.

-------------------------------------
Setup Instructions
-------------------------------------

1. Prerequisites:
   - Node.js v16 or higher
   - npm (comes with Node.js)
   - A Discord Bot Token (from the Discord Developer Portal)

2. Clone the Repository:
   ```git clone https://github.com/YourUsername/sydney-roleplay-bot.git```
   ```cd sydney-roleplay-bot```

3. Install Dependencies:
   npm install

4. Configure Environment:
   Create a file named ".env" in the project root and add:
   DISCORD_TOKEN=your-bot-token-here

5. Run the Bot:
   ```node srp.js```

-------------------------------------
Running with PM2 (Recommended)
-------------------------------------

1. Install pm2 globally (if not already installed):
   ```npm install -g pm2```

2. Start the bot with pm2:
   ```pm2 start srp.js --name "SydneyRoleplayBot"```

3. Save the pm2 process list (so it restarts on reboot):
   ```pm2 save```

4. Enable pm2 startup:
   ```pm2 startup```

-------------------------------------
Confirmation:
-------------------------------------
If setup is correct, you should see the bot come online in Discord and the console will show a success message.
