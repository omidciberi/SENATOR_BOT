# lua-api-bot

A simple telegram-bot wtitten in LUA

# commands

 **sticker to photo**

`just send a sticker`

 **photo to sticker**

`just send a photo`

  **bold text**

`/bold text`

 **italic text**

`/italic text`

 **markdown link**

`/link url text`

# channel

 **send bold text to a channel**

`/boldch @channelusername text`

 **send italic text to a channel**

`/italicch @channelusername text`

 **send markdown link to a channel**

`/linkch @channelusername url text`



# Installation

You should have [lua](http://www.lua.org/) installed

```bash
sudo apt-get install lua

```
Clone the bot

```
git clone https://github.com/Imandaneshi/file-manager-bot.git
cd file-manager-bot

```

Then install bot using

`bash launch.sh install`

bot token in bot.lua (config part)

```lua

local token = ""
local BASE_URL = "https://api.telegram.org/bot"..token
```

And enter your telegram-id in admins table in [bot.lua](https://github.com/Imandaneshi/file-manager-bot/blob/master/bot.lua#L19)
```lua
local var = false
  local admins = {123456789,987654321}-- put your id here
  for k,v in pairs(admins) do

```

Save bot.lua

Start the bot

`bash launch.sh`
