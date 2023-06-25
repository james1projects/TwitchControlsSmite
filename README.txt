This is still in first testing and may have unexpected issues.

SETUP:

1) This bot uses a Twitch account to connect to your channel to read chat. I recommend using a separate Twitch account than your broadcaster
channel for security reasons, but you can use the same channel if you'd like.

2) Go to https://twitchapps.com/tmi/ then click connect and login with the Twitch account you want this bot to use to connect to your chat.
You should see a oauth token that starts with "oauth:". Copy the ENTIRE token.

3) Open setup.ini and replace "YOUR TOKEN HERE" with the token you copied. 
Do not show this to anyone as it could give them access to the twitch account for sending messages and things like that.

4) Replace "BOT USERNAME HERE" with the username of the twitch account.

5) Replace "STREAMING USERNAME HERE" with your Twitch username, the channel you are streaming to.

6) Rename "setup.ini" to "config.ini".

You may notice there are other settings in the config, these are other things I have for my personal stream and they require additional setup to use. 
I'm still working on having an easier setup for them  to possibly release a version of the bot that include these features, 
but for now this version is only for allowing controlling movement, abilities, relics of Smite through twitch chat.


Try opening twitch_chat_bot.exe, then go to your twitch channel and type something in. The message should be displayed in the console as well. Then I would recommend opening Smite
and going into jungle practice, then on your phone open your twitch chat and try typing things like "1", "2", "3", "4" to see if it makes you use your abilities. 

Highly recommend having Smite set to quick or instant cast for this to work correctly. You can also open keyboard controller settings.ini to change any of the hotkeys or commands for
controlling Smite. keyboard controller settings.ini will only be created once a chat message has been typed in chat and the bot has successfully been connected.