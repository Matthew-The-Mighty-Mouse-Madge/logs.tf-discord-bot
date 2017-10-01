# logs.tf-discord-bot
A discord bot showing your recent logs, profile page and team matches. You can create teams, fill them with players and get recent matches of the teams. You can also search for other persons logs and logs.tf profile's.
 Can be run in the background on a raspberry pi or other server.

## Requirements
Your System (Computer/Server) needs: 
- Python 3.6 or higher
- discord.py libary (https://github.com/Rapptz/discord.py)


You need a bit of experience in JSON and general programming (so you can fill the token and your user correctly). Trust me this ins't that hard to do.

## Installation
###Easy Installation:
- Install Python3 and pip
- Insert the folder into your python directory
- Run "install.py"

###Manual Installation:
1. Install Python3 and pip

2. Go to your CMD and type `"py -m pip install discord.py"` and after that `"py -m pip install asyncio"`

3. Download this repository (*Use green "Clone or download" button*)

4. Insert the code into your python3 folder

5. Create a Discord Bot ([Tutorial](https://github.com/callFEELD/logs.tf-discord-bot/wiki/Create-a-DiscordBOT)) and let the bot join your server ([Tutorial](https://github.com/callFEELD/logs.tf-discord-bot/wiki/Let-the-Discord-Bot-join-your-server))

6. Put your bot's token into *token.json* ([Tutorial](https://github.com/callFEELD/logs.tf-discord-bot/wiki/insert-the-token-to-the-token.json-file))

7. Get your Discord ID (enable the developer mode in discord (Settings -> Appearance; scroll down and check "Developer Mode") after that you can rightclick on your profile in a server member list and hit "copy id") and SteamID64 and fill them into the users.json file inside the moderators object. ([Tutorial](https://github.com/callFEELD/logs.tf-discord-bot/wiki/insert-your-Discord-ID-and-Steam-ID-into-the-users.json-file))

8. Run the python script `bot.py`
