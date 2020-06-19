## Discord.js Command Handler
Hello and welcome to the quick tutorial on how to make a command handler in a github repo :D
This is a quick tutorial so don't expect this to be a full bot. you can easily install it and use it. It only has one "hi" command for a example. You might learn more about commands in some youtube/web tutorials. I also recommend going to: https://discord.js.org

## Installing Packages
To get the gtihub repo use: `$ git clone https://github.com/eeelolmeisbol/discord.js-command-handler`
 Then Use: `npm install discord.js` to install discord.js packages.

Now thats all! lets get into getting our bot token and editing some files.

**Getting ur bot token**
Go to: https://discord.com/developers/applications

After that you will see this, go and click create new application. Go in it and then open `Bot`
![/Users/aysuyildiz/Desktop/Bildschirmfoto\ 2020-06-18\ um\ 23.01.00.png]()

![/Users/aysuyildiz/Desktop/Bildschirmfoto\ 2020-06-18\ um\ 23.02.54.png](yes)
After that you will see this, go and click **create bot** copy the **token** after that go to `OAuth2` page.

Go to __Scopes__ and check BOT. After that copy the link that showed up and paste it into a website url. the invite the bot.


## Config
In the config.json file you will see this:

     {
    "token": "YOUR_TOKEN_HERE",
    "prefix": "n? (YOUR PREFIX)",
    "discord_owner_id": "YOU_ID_HERE"
     }

**Replace discord_owner_id with ur id. ( Right click ur avatar and click "Copy ID"**

**Replace prefix with ur command prefix. (so if you put ! it will be !help)**

**Replace token with ur bot token. (Paste the token from developer portal.)

## Starting
You can simply start it by doing: `node .`

***Now youre all done! you can now add as many commands as you want :)***
