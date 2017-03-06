# sticker bot
sticker bot help you to convert your photo to sticker or inverse
base on lua - use otouto function - TELEGRAM BOT

# commands & action 

 **sticker to photo**

`send a sticker , will convert to photo`

 **photo to sticker**

`send a photo , will convert to sticker`

 **/start** & **/help** 
 
 `show the help message`


# Installation

```bash
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev

```
`sudo apt-get install lua-socket` 
`sudo apt-get install lua-sec`

```
git clone https://github.com/iamjavid/sticker_bot.git
cd sticker_bot

```

enter bot token in the bot.lua

```lua

local bot_api_key = "" -- token
local BASE_URL = "https://api.telegram.org/bot"..bot_api_key
```

enter your telegram id as admin
```lua
local var = false
  local admins = {0}-- put your id here
  for k,v in pairs(admins) do

```

Save bot.lua

Start the bot

`lua bot.lua`


Developer : [JAVID](https://telegram.me/jwdmo)
