# DemaBot
## A French shitposting bot for Discord.

Don't you always wanted a good shitposting bot ? All in French even ? Then DemaBot is for you !

Wrote entirely with Javascript, NodeJS and the DiscordJS v14.3 library.

## All commands available :

### Shitposting
```/decrypte``` - The well known french YouTuber named Hugo Decrypte is going to tell you a silly sentence ! All in french though.

```/dox``` - Posts an image of earth subtitled with a fake IP Address (as to not really dox someone).

```/ville``` - Upload an image, and a text to it. It combines them chaoticaly.

### Administration (needs adiministration role)
```/ban``` - Bans a member from your Discord server 

```/kick``` - Kicks a member from your Discord server

## Bot Link :
Link to invite the bot :
* [Link](https://discord.com/oauth2/authorize?client_id=1352966901567066173&permissions=0&integration_type=0&scope=bot)

It needs Administrator requirement as there is still a ban and kick command, and might need those for further developement.

## How to deploy :
Make sure you have Node and npm installed, you can find them here : [NodeJS.org](https://nodejs.org/fr/download)

You need to have made a Discord Bot in [Discord Developper Portal](https://discord.com/developers/applications)

* Pull the Git repo in an empty folder.
* Open this folder in a Terminal
* Type ```npm install``` (it will download all the packages required)
* Create a .env file
* It should looks like this :

  <img width="343" alt="image" src="https://github.com/Minkavi/BadeBot/assets/119850615/1ea94d95-192f-4c89-8f93-ba4704fe8efa">
* To deploy commands : ```node deploy_command.js```
* To delete commands : ```node delete_command.js```
* To run the bot : ```node .```or ```node index.js```

Enjoy your new bot.

made by little fragile french hand of dematia
