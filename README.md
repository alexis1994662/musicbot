# musicbot


Make sure you have the bot set up correctly on discord.

Must have ffmpeg installed on your comp
	https://www.gyan.dev/ffmpeg/builds/

using vs studios
	in the terminal type npm install node.js dotenv discord.js discord-player @discordjs/voice @discordjs/rest @discordjs/opus @discordjs/builders ffmpeg
	
3 things youll need to change 
In the .env file enter your token with no " " 
on the index.js file //lines 13 and 14 you need to update:
	CLIENT_ID = this is the same as application id under general information where you set up your bot 
	GUILD_ID =  make sure your discord is set up in developer mode -> click the settings gear by your username on the bottom left then 
	advance then turn developer mode on // after thats done right click on your server name and click copy ID. 

To run:
first type in the terminal "node index.js load"
this turns on the slash commands

then type node index.js
and this turns on your bot 
