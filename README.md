## Discord-Join-to-Create

A basic Join to Create Bot, Which works perfectly finem, Easy to setup!

## Installation | How to use the Bot

 **1.** Install [node.js v12](https://nodejs.org/api/cli.html#cli_unhandled_rejections_mode) or higher

 **2.** Download this repo and unzip it    |    or git clone it
 
 **3.** Install all of the packages with **`npm install`**     |  the packages are   **`npm install node.js discord.js`**
 
 **4.** start the bot with **`node index.js`**

## Usage - index.js

```javascript
const Discord = require("discord.js");          //load the Discord.js Library
const client = new Discord.Client();            //make a new Client
const config = require("./config.json");        //load in all of the config files
client.on("ready", ()=>console.log("READY"));   //log when the bot gets ready
const jointocreate = require("./jointocreate"); //load the jointocreate.js file
jointocreate(client);                           //call the jointocreate file
client.login(config.TOKEN);                     //start the bot with the bot token
```

## **NOTE:**

*If you are having errors/problems with starting delete the package.json file and do, before you install the packages `npm init`*

## SUPPORT ME

You can always Support me by inviting one of my **own Discord Bots**

[![Musicium Music Bot](https://cdn.discordapp.com/attachments/742446682381221938/770055673965707264/test1.png)](https://bit.ly/Musicium)
[![Milrato Muslti Bot](https://cdn.discordapp.com/attachments/742446682381221938/770056826724679680/test1.png)](https://bit.ly/Milrato)

[| fork my repository  |](https://github.com/user/repository/fork)
[watch this repo  |](https://github.com/user/repository/subscription)
[create issue |](https://github.com/user/repository/issues/new)

*Both bots are still in Development, and will always be in development, this means always uptodate and always online and always improving!*
