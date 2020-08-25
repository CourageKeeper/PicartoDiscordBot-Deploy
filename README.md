README

-----

Update:
This bot is current still limping along but does not function realiably. Discord has changed their heartbeat API so it often shows as offline, although it notifies more often than not. There is also an issue with the database occasionally permitting duplicate keys, thus duplicating notifications.
Discord has also announced an API overhaul in November 2020. If I do not find time to update it before then it will become entirely non-functional and will be taken offline.

-----

This is version 2 of the Picarto/Discord interface bot.
The two primary differences between the test version and this are:

1. It uses NeDB as an in-memory database to manage the servers, streamers, and their online states.

2. It interfaces with Picarto's public API, allowing it to be configured by the end users.

Description:

The Picarto We're Live! bot allows a Discord server owner to join the bot to their channel and set it up to notify a text channel when a streamer goes live on Picarto.tv.


Currently the bot uses @here to announce streams and will fail if Mention Everyone is not allowed.

Once this bot has been added to a server, it will need to be configured for each streamer. Send it a DM via Discord to get started. It will respond to your messages and walk you through setting up a streamer. Once you get the hang of things, try the [quickadd] command to speed things up if you're adding multiple streamers.

It defaults to the default text channel that is first created with the server. To choose the channel, use the [setBotChannel] command and give it the channel ID you'd like to use.

If you run into any problems you may either DM me on Discord, open an issue on GitHub, or send an email to dannfirefeet[at]gmail.com if you prefer.
