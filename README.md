![](https://s3.amazonaws.com/files.enjin.com/778581/Final%20DEFR%20Logo/Logo-DEFR.png)

# [Dead Friends Gaming - Discord commands guide](https://discord.link/defr "Click to open the DEFR Discord")

  

### This is a list of the commands that can be used to control the server. You cannot use commands in private messages. Not every command starts with the same prefix, but most are `!`. Required parameters are indicated with `<` and `>`, while optional parameters are indicated with `[` and `]`. Please remember to use commands only in the *#bot-cmds* channel.

  

## General

-  `!help [category]` - Prints a list of commands.
-  `!info [page]` - Prints a list of info pages. [!] THIS CMD IS NOT FINISHED [!]
-  `%apply` - Start a member application in DM. (Make sure you have dm's enabled in privacy settings for this server).
-  `!ping` - Returns the bot response time.
-  `!levels` - Get a link to the leaderboard.
-  `!rank <optional user>` - Get the rank of anyone in the server.


  ---
  
  
## Music

-  `!play <URL/query` - Plays audio from a specific URL or searches for a query on YouTube and queues the first result.
-  `!queue` - Displays all of the media that is queued.
-  `!np` - Displays the media that is currently being played.
-  `!skip` - Vote to skip the current media.

  

### Music - Member only commands

-  `!skip f` - Instantly skip the current media.
-  `!search [service] [#] <query>` - Searches a specific service (default: YT) for a query and returns the first few results (default: 3, limit: 10). The user can then select from the results if they want to add any to the queue.
-  `!shuffle` - Shuffles the queue.
-  `!clearqueue` - Clears the queue.
-  `!pause` - Pauses the current media. (Media auto pauses when the channel is empty)
-  `!resume` - Resumes the current media. (Media auto resumes when joining the channel if it was auto paused)
-  `!summon` - Connects the bot to your current voice channel, if it has permission.
-  `!blacklist <status> <@user1>...` - Add or remove users from the blacklist. Blacklisted users cannot use any bot commands. This overrides any permissions settings set in the permissions file. The owner cannot be blacklisted. Multiple users can be specified in the command. Users must be @mentioned. Status should be either `+`, `-`, `add`, or `remove`.
-  `!stream <url>` - Streams a URL. This can be a Twitch, YouTube, etc livestream, or a radio stream. This feature of the bot is experimental and may have some issues.
-  `!remove <number>` - Removes a song from the queue by its numbered position. Use ``!queue` to find out song positions.
- `!karaoke` Activate or deactivate karaoke mode. (During karaoke mode, only members can queue music.

  

## Games

#### Music Quiz

-  `!start-quiz` - Start a Music Quiz game in your voice channel. (Channel must be either *Tesla* or *Einstein*.)
-  `!pass` - Start a vote to pass a song.

**Games - Member only commands**
-  `!stop-quiz` - Stop the current Music Quiz game.

  
  

## Member only commands

**Recording voice channels**

-  `!record` - Have MEE6 connect to your voice channel and starts a recording. (Channel must be either *Tesla*, *Einstein* or a meeting channel.) **(You need to warn every user that is connected that they are being recorded!)**
-  `!stop-recording` - Stop the current recording.

  

**User Management**

-  `!infractions [user]` - Displays how many infractions a user has and the reason if specified.
-  `!tempmute [user] [duration] <optional reason>` - Temporally mute a user with an optional reason.
-  `!unmute [user]` - Unmute a user.
-  `!warn [user] <optional reason>` - Warn a user.
-  `!slowmode [timeout]` - Enables/Disables slowmode in a channel. (Time in seconds a user has to wait in between sending messages. To disable use `!slowmode off`.


**Channel / message management**

-  `!announce [message]` - Send an announcement message to the *#announcements channel*
-  `!clear <@user> [ammount]` - Clear x messages (optional from the mentioned user) in the current channel.
- `!create-forum [forum-name] [public/private] [Your forum topic.]` - Create a public or private (member only) text channel.

**Tickets**

- `!tclose` - Close a support ticket and auto delete it.
- `treply [message]` - Reply to a ticket.

**Server Management**

- `!gadmin` - Give yourself the *admins* role.  (🛑 This grants you nearly full admin permissions to the server and bots. You should avoid having this enabled for your role. However, if you are 100% sure what you are doing, you can go ahead 😊! Just be aware that you don't delete messages or stuff. Since this is most likely irreversible!)
- `!radmin` - Remove the *admin* role from yourself.

## Admin only commands
Note: these commands only work if you have the administrator permission. The *admins* role does not have administrator permission.

`!role [@user] [role]` - Adds the role to the mentioned user, if the user already has the role then it removes it from them.



<div style="background-image: url('https://s3.amazonaws.com/files.enjin.com/778581/Final DEFR Logo/AVI-2.jpg');">
******************
Last updated on June, 5 2020
Made by: dangerBEclose
