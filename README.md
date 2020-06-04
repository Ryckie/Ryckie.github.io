![](https://imgur.com/S9EY6m3.png)
# [Dead Friends Gaming - Discord commands guide](https://discord.link/defr "Click to open the DEFR Discord")

### This is a list of the commands that can be used to control the server. You cannot use commands in private messages. Not every command starts with the same prefix, but most are `!`. Required parameters are indicated with `<` and `>`, while optional parameters are indicated with `[` and `]`. Please remember to use commands only in the *#bot-cmds* channel.

## General
- `!help [category]` - Prints a list of commands.
- `!info [page]` - Prints a list of info pages.
- `%apply` - Start a member application in DM. (Make sure you have dm's enabled in privacy settings for this server).
- `!ping` - Returns the bot response time.
- `!levels` - Get a link to the leaderboard.
- `!rank <optional user>` - Get the rank of anyone in the server.

### Members only
- `!announce [message]` -  Send an announcement message to the *#announcements channel*
- `!clear <member> [ammount]` - Clear x messages in the current channel. (Mention a member to delete x amount of messages from that member only.

## Music
- `!play <URL/query` - Plays audio from a specific URL or searches for a query on YouTube and queues the first result.
- `!queue` - Displays all of the media that is queued.
- `!np` - Displays the media that is currently being played.
- `!skip` - Vote to skip the current media. 

### Music - Member only commands
- `!skip f` - Instantly skip the current media.
- `!search [service] [#] <query>` - Searches a specific service (default: YT) for a query and returns the first few results (default: 3, limit: 10). The user can then select from the results if they want to add any to the queue.
- `!shuffle` - Shuffles the queue.
- `!clear` - Clears the queue. (Not to con
- `!pause` - Pauses the current media. (Media auto pauses when the channel is empty)
- `!resume` - Resumes the current media. (Media auto resumes when joining the channel if it was auto paused)
- `!summon` - Connects the bot to your current voice channel, if it has permission.
- `!save` - Save the current song to the autoplaylist.
- `!blacklist <status> <@user1>...` - Add or remove users from the blacklist. Blacklisted users cannot use any bot commands. This overrides any permissions settings set in the permissions file. The owner cannot be blacklisted. Multiple users can be specified in the command. Users must be @mentioned. Status should be either `+`, `-`, `add`, or `remove`.
- `!stream <url>` - Streams a URL. This can be a Twitch, YouTube, etc livestream, or a radio stream. This feature of the bot is experimental and may have some issues.
- `!remove <number>` - Removes a song from the queue by its numbered position. Use ``!queue` to find out song positions.

## Games
#### Music Quiz
- `!start-quiz` - Start a Music Quiz game in your voice channel. (Channel must be either *Tesla* or *Einstein*.) 
- `!stop-quiz` - Stop the current Music Quiz game.
- `!vote-skip` - Start a vote to skip to the next song.


## --- Member only commands ---
**Recording voice channels**
- `!record` - Have MEE6 connect to your voice channel and starts a recording. (Channel must be either *Tesla*, *Einstein* or a meeting channel.) **(You need to warn every user that is connected that they are being recorded!)**
- `!stop-recording` - Stop the current recording.

**User Management**
- `!infractions [user]` - Displays how many infractions a user has and the reason if specified.
- `!tempmute [user] [duration] <optional reason>` - Temporally mute a user with an optional reason.
- `!unmute [user]` - Unmute a user.
- `!warn [user] <optional reason>` - Warn a user.
- `%accept`
- `!slowmode [timeout]` - Enables/Disables slowmode in a channel. (Time in seconds a user has to wait in between sending messages.  To disable use `!slowmode off`.

**Other**


<!--stackedit_data:
eyJoaXN0b3J5IjpbNTk4ODQzODA2LC00MjI5MzU5NjAsMTQzMD
M4NjU5MiwyMDY1OTc5NDQyXX0=
-->