<h1 align="center">Telegram File Stream Bot</h1>


## Make Your Own

Either you could locally host or deploy on [Heroku](https://heroku.com/deploy?)

### Deploy to Heroku 🏃‍♂

The easiest way to deploy this Song Bot  <br><br>
[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/oVoIndia/oVo-FileStreamBot)

Then Goto The <a href="#mandatory-vars">Variables Tab</a> For More Info On Setting Up Environmental Variables.


### Heroku web Server Sleeps after 30 minutes. You can Ping if to Keep it always Active. I am also doing same thing.  



### Mandatory Vars

`API_ID` : Goto [my.telegram.org](https://my.telegram.org) to obtain this.

`API_HASH` : Goto [my.telegram.org](https://my.telegram.org) to obtain this.

`BOT_TOKEN` : Get the bot token from [@BotFather](https://telegram.dog/BotFather)

`LOG_CHANNEL` : Create a new channel (private/public), add [@missrose_bot](https://telegram.dog/MissRose_bot) as admin to the channel and type /id. Now copy paste the ID into this field.

`OWNER_ID` : Your Telegram User ID

`DATABASE_URL` : MongoDB URI for saving User IDs when they first Start the Bot. We will use that for Broadcasting to them. I will try to add more features related with Database. If you need help to get the URI you can ask in [Support Group](https://t.me/hxsupport}.

### Optional Vars

`JOIN_CHANNEL`  : Put a Public Channel Username, so every user have to Join that channel to use the bot. Must add bot to channel as Admin to work properly.

`BANNED_CHANNELS` : Put IDs of Banned Channels where bot will not work. You can add multiple IDs & separate with <kbd>Space</kbd>.

`SLEEP_THRESHOLD` : Set a sleep threshold for flood wait exceptions happening globally in this telegram bot instance, below which any request that raises a flood wait will be automatically invoked again after sleeping for the required amount of time. Flood wait exceptions requiring higher waiting times will be raised. Defaults to 60 seconds.

`WORKERS` : Number of maximum concurrent workers for handling incoming updates. Defaults to `3`

`PORT` : The port that you want your webapp to be listened to. Defaults to `8080`

`WEB_SERVER_BIND_ADDRESS` : Your server bind adress. Defauls to `0.0.0.0`

`NO_PORT` : If you don't want your port to be displayed. You should point your `PORT` to `80` (http) or `443` (https) for the links to work. Ignore this if you're on Heroku.

`FQDN` :  A Fully Qualified Domain Name if present. Defaults to `WEB_SERVER_BIND_ADDRESS`

## How To Use The Bot

:warning: **Before using the  bot, don't forget to add the bot to the `JOIN_CHANNEL` as an Admin**
 
`/start` : To check if the bot is alive or not.

To get an instant stream link, just forward any media to the bot and boom, its fast af.

### Channel Support
Bot also Supported with Channels. Just add bot Channel as Admin. If any new file comes in Channel it will edit it with **Get Download Link** Button.

### Credits:

- Original Coders

### Developed By:

-  [oVo-HxBots](https://github.com/oVo-HxBots)
-  [Kirodewal](https://t.me/Kirodewal)
-  [oVoIndia](https://github.com/oVoIndia)
-  [HxBots](https://t.me/HxBots)

### Demo Bot

-  [@oVo_FileStreamBot](https://t.me/oVo_FileStreamBot)