# Whats changed?
there are no admin commands, no welcome commands, all of the unecessary stuff
has been redacted. This version of the bot is what most will end up using.
This branch was developed using anonymous data that was gatherd concearning
the way users ineract with the bot, and using this data I removed the features
that our users do not use, or have other bots perform for them.
TLDR: removed unecessary junk most users dont need.
# Hentai discord bot 
This bot is a cooperative effort between Phi and Eddy :). 
## functionality 
 
it can do some social stuff,
it can do le epic hentai stuff
its quite good at moderating
and it logs everything said in  chat into a txt file.

## Live instances
### currently, there is one instance of the bot,
which you can add to your server using this link.
[HERE](https://github.com/Eddy-Arch/Hentai-discord-bot/blob/experimental/docs/INSTANCES.md) you can find a list of all the live instances.

- [Invite the bot to your server](https://github.com/Eddy-Arch/Hentai-discord-bot/blob/experimental/docs/INSTANCES.md)
### Disclaimer:
The bot is intended to be hosted individually for one server.
The bot by design also logs all messages sent in a discord server.
I highly recommend you start your own instance, otherwise, just add the current
one.
If you would like to submit an instace, add it to the INSTANCES.md file,
and then open a pull request about it.


<!---
## website
- the bot has an offical website! heres a link: https://hentai-distributor.glitch.me/
## invite code
- [Invite the bot to your server](https://discordapp.com/oauth2/authorize?client_id=610938779401846804&scope=bot&permissions=8)
-->



## full feature list:

- a bunch of hentai commands
- a bunch of lewd commands
- some social commands, such as hug, kiss, etc. 
- basic moderation, such as kick, ban, warn. ban and kick send a message with the reason for the ban/kick, before removing the user.
- built in coronavirus tracker
- has terry a davis "words from god" command.
- logs every single message into the console, and into a text file. 


## install guide:
### to install this on baremetal/server/selfhost, run the following commands: 
```bash
git clone https://github.com/Eddy-Arch/hentai-discord-bot.git
```

```bash
cd hentai-discord-bot
```

```bash
pip3 install -r requirements.txt
```

```bash
nohup python3 index.py
```

### heroku install
more advanced users may wish to install the bot on heroku, and other
git using hosting services.
this repo contains all the files necessary for you to be able to just
commit the bot to your heroku server, and it should work out of the box.
(Procfile, requirements.txt)
## Main idea behind the bot
### most bots on discord nowadays are:
- overly complex
- are made up of multiple files
- are hard to edit
- have more than 10k LOC
#### the main idea behind this bot is its simple to edit/audit and understand
#### there are no cogs, no 10k+ files and lines of code, making customization
#### a breeze.

## FAQ
### invalid token:
the bot needs a working token, to get one, create a developer account 
on discord and insert the token in config.py
### discord.py error
you need to update discord.py. you can do this by running
```pip3 install discord.py```

## Donate

- [Donate to the project](https://github.com/Eddy-Arch/Hentai-discord-bot/blob/master/docs/CREDITS.md)
## Versions
Currently, new branches are being developed without admin/social/nsfw options.
Check out the branches page for more info.
