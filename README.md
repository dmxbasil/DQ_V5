<h1>πΏπ π½ππ


## Features

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Pm File search
- [x] Inline Search
- [x] Single Start pic
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel
- [x] Spelling Check Feature
- [x] File Store
- [x] Carbon
- [x] Sticker id
- [x] Lyrics , Song
- [x] TTS
- [x] Redirect Chat
- [x] Covid
- [x] Totally Customisable Bot

## π π¨π¦π§ ππ’

π½πππππ πΏπππππ πππ ππππ ππΏππ ππππ ππ [ππππ ππππ](https://github.com/DKBOTx/TovinoBotV3/blob/8a258fb9e2c92fdb8e78b465642e18f9f47b6dce/plugins/pm_filter.py#L444) ππ ππππ πππΏππππΎπ πΎππΌππππ ππππ . πππππππππ πππ πΎπΌππ ππΌππ πππππ ππππ πΎππΌππππ

πππππ ππππ π½πππ , ππππ πΌππΏ πΏπππππ πππ πππ. ππππ π½π πππππΏ π€§

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). 
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). 
* `DELETE_TIME` : Autodelete Time in seconds 
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
* `AUTH_CHANNEL` : Custom Fsub Channel , Redirect Channel Too
### Optional Variables
* `PICS`: Telegraph link of image to show in start message.( Multiple images can't be used )
* `REDIRECT_TO` : Redirect Var Set value 0 if Redirect not required
* `FILE_STORE_CHANNEL`: Channel from were file store links of posts should be made.Separate multiple IDs by space
* Check `info.py` in this code for more variables


## Deploy
You can deploy this bot anywhere.



<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/DKBOTx/TovinoBotV3
# Install Packages
pip3 install -U -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>

ππππ πΌππΏ πππ½ ππππ πππΌππ ππ

## Commands
```
β’ /logs - to get the rescent errors
β’ /stats - to get status of files in db.
* /filter - add manual filters
* /filters - view filters
* /connect - connect to PM.
* /disconnect - disconnect from PM
* /del - delete a filter
* /delall - delete all filters
* /deleteall - delete all index(autofilter)
* /delete - delete a specific file from index.
* /info - get user info
* /id - get tg ids.
* /imdb - fetch info from imdb.
β’ /users - to get list of my users and ids.
β’ /chats - to get list of the my chats and ids 
β’ /index  - to add files from a channel
β’ /leave  - to leave from a chat.
β’ /disable  -  do disable a chat.
* /enable - re-enable chat.
β’ /ban  - to ban a user.
* /carbon - create carbon
* /settings - customise chat settings
* /tts - text to speech
* /short - link shorter
β’ /unban  - to unban a user.
β’ /channel - to get list of total connected channels
β’ /broadcast - to broadcast a message to all Eva Maria users
β’ /batch - to create link for multiple posts
β’ /link - to create link for one post
```
