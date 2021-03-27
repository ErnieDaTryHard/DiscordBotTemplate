# DiscordBotTemplate

A simple template to get you started with discord.js.

## Requirements

* [Node.JS](https://nodejs.org/ "Node.JS") v12 or higher (This particular version uses Node.JS v14.15.1)
* A sufficient text editor. I suggest [Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code") however [Sublime Text](https://www.sublimetext.com/ "Sublime Text") and [Atom](https://atom.io/ "Atom") are great alternatives.
* A Discord account
* Some knowledge on the discord.js library. If this is your first time, documentation for discord.js can be found [here](https://discord.js.org/#/docs/main/stable/general/welcome "here").

## Setup

_Disclaimer: This is a bare bones setup for a discord bot, and I will not be teaching you how to use the discord.js library. However, I will be teaching you how to use this template for a simple command handler for your projects. For more advanced projects, I suggest using [WOKCommands](https://github.com/AlexzanderFlores/WOKCommands "WOKCommands") as it has a better command handler system, database intregration and much more._

1. Clone or install this repository locally to your machine.

This can be done via:
- `git clone https://github.com/ErnieDaTryHard/DiscordBotTemplate.git` on the command line (if you have git installed)
- Through `GitHub Desktop`
- Downloaded as a zip from this repository page (be sure to rename the files to not have -master as this can mess up the file system later on)
 
2. Install the required dependencies. This can be done by running `npm install` on the command line in our cloned / downloaded directory.

3. Create a new application for your discord bot. Visit the [Discord Dev Portal](https://discord.com/developers/applications "Discord Dev Portal") to create a new application.

Once created, go to the bot tab and create a new bot. Then copy the bot's token and paste it into the package.json file where it says "paste token here"

_Note: __DO NOT__ share your bot token with anyone. Treat it as your password for your bot. If people have your bot token, all progress that you have made into developing your Discord Bot can be destroyed in an instant with API abusers. This can get your discord account banned as the bot is tied with your account._

4. We need to invite our discord bot to a server in order to start development. To do this, visit the [Discord Permissions Calculator](https://discordapi.com/permissions.html "Discord Permissions Calculator") and insert your client ID here: 

![](https://i.imgur.com/MxORJkG.png)

Your client ID can be found in the `General Information` tab of your application in the Discord Dev Portal.

Next, add all the required permissions your bot needs in order to do what you intend for it to do. If your bot doesn't have sufficient permissions for an action you are trying to perform, then it will throw an error. In our case, we will select only the Administrator permission as we are developing our bot and we want it to be able to achieve anything that is necessary to complete an action. How you choose to setup your permissions when you release your bot publicly is up to you.

Copy the link generated at the bottom and open it in a new tab. This will give you a bot invite, so you can invite it to your testing server.

5. Let's make sure our bot is functioning. Run `node .` on the command line in your bot directory to start up your bot. In your testing server you should see your bot going online, which is a good sign. In any of your text channels, type `!ping`. If the bot responds with `pong!`, then your bot is succesfully up and running. To shut down your bot, go back to the command line and enter `Ctrl + C`.

Great! Your bot is now up and running and you can now code your commands with a simple command handler. For guides on the discord.js library use [Youtube](https://www.youtube.com/results?search_query=discord.js+bot+tutorial "Youtube"). 






