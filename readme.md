# Discord Gopher Bot

### What do we want?

I want a discord bot that will;

- Display a drawn gopher when we enter !gopher
- Display a list of gophers available when we enter !gophers
- Display a random gopher when we enter !random
- It will also be hosted in the cloud

### Packages Used

When writing this, I used the folloing resources;

- [DiscordGo](https://github.com/bwmarrin/discordgo) // DiscordGo is the most comprehensive Go Package that provides low level bindings to the Discord chat client API. It has nearly complete support for all of the Discord API endpoints, websocket interfaces, and voice interfaces.
- [Kutego API](https://github.com/gaelleacas/kutego-api) // KuteGo is an API to play around with [Aurelie Vache's Gophers](https://github.com/scraly/gophers)

## Discord Prerequisites

You'll of course need a discord account, so if you don't have one it's easy enough to create.

### Enable Developer Mode

You'll need to enable developer mode within the client so that you have sufficient rights.

- Click on User Settings

  ![](https://i.imgur.com/wlmAXcy.png)

- Click on Advanced and then enable Developer Mode

  ![](https://i.imgur.com/DEfkpmF.png)

### Create a Discord Application

Go over to the [Discord Developer Portal](https://discord.com/developers/applications/), then click on New Application up on the top right. Give your application a name, accept the terms and click create.

![](https://i.imgur.com/aBRQ5DV.png)

You can now give it an App Icon, descripton and some tags if you wanted.

![](https://i.imgur.com/aGGmV4B.png)

### Create A Bot

Click on the Bot menu on the left and then click Add Bot.

![](https://i.imgur.com/C8Rb2M4.png)

You'll then have your bot added to your application :-)

![](https://i.imgur.com/NJKD97g.png)

We now need to give the bot permissions, and I found this step tricky at first. So head over to OAuth2 and within the dropdown of Authorisation Method, select In-app Authorisation, then tick the bot scope.

![](https://i.imgur.com/q3LDmju.png)

Now you'll see more options for bot permissions. Now I trust this bot (for now), and so I ticked the Administrator permissions. Click Save Changes when you're done.

![](https://i.imgur.com/CpTEPFq.png)

### Invite Your Bot

Still within the OAuth2 menu, click on URL Generator. The scope you want is bot, and bot permissions is Administrator.

![](https://i.imgur.com/9tZ64wK.png)

Once this is done, you'll have a Generated URL at the bottom of the page. Copy this URL and put it into your browser. You'll then be able to add the bot to whichever server you have permissions in.

![](https://i.imgur.com/MYsTqQB.png)

There we go, you should now see your bot within your discord server, showing offline.

![](https://i.imgur.com/oIUGzN1.png)
