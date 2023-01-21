# AutoSendDiscordMessage
A simple Python code to send a message with your discord account every set amount of time, without having to be online.

- Support: https://discord.gg/3qvpkgWSbF
# Setup
1. Fill Out The Config In `config.json`
2. Run `python main.py`
3. Done! If you want to change more then that is fine!
# How To Get Discord Token
1. Go on [Discord Web](https://discord.com/app) and open [Console](https://www.youtube.com/watch?v=nFFKnWw-_Ys&ab_channel=MDTechVideos)
2. In console paste the following command: `webpackChunkdiscord_app.push([[""],{},req=>copy(Object.values(req.c).find(x => x?.exports?.default?.getToken).exports.default.getToken())])`
3. Now your token should be coppied to your clipboard!
# How To Send Messages To Users
1. Go on [Discord Web](https://discord.com/app) and go to the user you want to dm. Then copy the numbers at the end of url, for example `https://discord.com/channels/@me/1024353330987802664` you would copy `1024353330987802664`
2. Paste it into the config. Simple!
