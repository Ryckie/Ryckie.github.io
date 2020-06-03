![](https://imgur.com/MqOzqSD.png)
# [Dead Friends Gaming - Discord commands guide](https://discord.link/defr "Click to open the DEFR Discord")

This is a list of the commands that can be used to control the server. You cannot use commands in private messages. Not every command starts with the same prefix, but most are `!`. Required parameters are indicated with `<` and `>`, while optional parameters are indicated with `[` and `]`.

## General
`!help` - Prints a list of commands, or info on a command if one is specified.
`!ping` - Returns the bot response time.

## Music
- `!play <URL/query` - Plays audio from a specific URL or searches for a query on YouTube and queues the first result.
- `!queue` - Displays all of the media that is queued.
- `!np` - Displays the media that is currently being played.
- `!skip` - Vote to skip the current media. Required skips/skip ratio is set in the config file. The bot’s owner will instantly skip when using `!skip f`.
- `!search [service] [#] <query>` - Searches a specific service (default: YT) for a query and returns the first few results (default: 3, limit: 10). The user can then select from the results if they want to add any to the queue.
- `!shuffle` - Shuffles the queue
- `!clear` - Clears the 
- `!pause` - Pauses the current media.
- `!resume` - Resumes the current media
- `!summon` - Connects the bot to your current voice channel, if it has permission.
- `!blacklist <status> <@user1>...` - Add or remove users from the blacklist. Blacklisted users cannot use any bot commands. This overrides any permissions settings set in the permissions file. The owner cannot be blacklisted. Multiple users can be specified in the command. Users must be @mentioned. Status should be either `+`, `-`, `add`, or `remove`.
- `!stream <url>` - Streams a URL. This can be a Twitch, YouTube, etc livestream, or a radio stream. This feature of the bot is experimental and may have some issues.
- `!remove <number>` - Removes a song from the queue by its numbered position. Use ``!queue` to find out song positions.


    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

### End
