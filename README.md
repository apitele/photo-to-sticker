# sticker bot
مرحبا بك في بوت التوحيل انا احول لك الملصق الى صوره والعكس (channel)[t.me/programmer_iraq]
 - TELEGRAM BOT
#الاوامر
 **ملصق الى صوره** 
ارسل ملصقا.       

 **صوره الى ملصق**

ارسل صوره
 **/start** & **/help** 
 
 `اظهار النساعده
# التنصيب

```bash
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev

```
`sudo apt-get install lua-socket` 
`sudo apt-get install lua-sec`

```
git clone https://github.com/apitele/photo-to-sticker.git
cd photo-to-sticker
```

ضع توكنك في  bot.lua

```lua

local bot_api_key = "التوكن هنا" -- token
local BASE_URL = "https://api.telegram.org/bot"..bot_api_key
```

 ضع الايدي الخاص بك
```lua
local var = false
  local admins = {0}-- put your id here
  for k,v in pairs(admins) do

```

احفظ bot.lua

شغل   البوت من خلال 👇

`lua bot.lua`ا
Developer : [programmer of iraq](https://telegram.me/programmer_iraq)
