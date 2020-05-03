# Elisa public repository
## Current version: 0.9 release

This is the official repository of the discord bot 'Elisa'. In the ''Issues tab, you can leave an error message and I will definitely consider it. Thanks.

> Invite link - https://discordapp.com/oauth2/authorize?client_id=696934742876225566&scope=bot&permissions=305145856

  ## Main commands
>> __Square brackets ( [] ) are used to indicate the value you must type. When using the command, *you do not need to write them*! For example: e!DJrole [@role], you should type e!DJrole @DJ__

### Admins commands
More admin commands in 'settings commands'

- e!install - Install bot music interface the current channel [Only admins/DJ's can use this]

- e!DJrole [@role] - Gives this role the permission to full control of the bot [Only admins can use this]

- e!prefix [prefix] - Change bot prefix. If [prefix] is empty, then bot will display your current prefix (this command will also work with the 'e!' prefix, even if you change it)

- e!addrole [level] [@role] - Set role as a reward for get this level

- e!removerole [level] - Reset the role for getting this level

- e!roles - Get a message with data on levels and their roles

- e!autoclear - Disabling/enabling clearing old roles, gotten from level up's, when you reach a new level role (default: enabled)

- e!notifications - Disabling/enabling bot notifications (level up, music initialize) (default: enabled)

- e!levels [enable/disable] - Enabling/disabling levels-roles system on this channel (default: enabled)
***
### Default commands

- e!help (e!ru_help for russian language) - Message with all bot commands with explanations

- e!user - Get some information about mentioned user

- e!pay [amount] [@user / userid] - Transfer money to another user (money displayed in e!user)

Funny commands

- e!kiss [@user] - Kiss the user (who would have thought?)

- e!hug [@user] - Hug the user
***
### Music interface commands

- e!uninstall - Uninstall music interface (the bot will accept this channel like any other)

- e!image [image URL] - Change background image for interface (shows when song queue is empty). Preferably use 'imgur' or 'yapx' **[only for admins]**

- e!skip - Skip current song (instead of this command i recommend using ⏭️ button in UI)

- e!stop - Clear the song queue (instead of this command i recommend using ⏹️ button in UI)

- e!autoleave - Disabling/Enabling auto leave from voice channel, when song queue is empty (default: disabled)

- e!skipto [number] - Skip songs before to the selected

- e!remove [number] - Remove picked song from the queue

- e!last - Add last played song to the queue

- e!vol [volume%] - Sets the music volume

- e!move [song1] [song2] - Move the song1 to song2 place in queue

- e!replace [song1] [song2] - Replace the song1 to song2

Playlists commands

- e!pl_add [num / num1-num2] - Add selected songs from song queue to playlist

- e!pl_get [@user] - Get your playlist, or playlist of mentioned user (if him playlist is public)

- e!pl_play [num / num1-num2] [@user] - Add song/songs of playlist to the song queue (if you haven’t specified a number, the full playlist will added to queue, and if you don't pick a user, your playlist will be playing)

- e!pl_private - Set your playlist private/public

- e!pl_remove [num / num1-num2] - Remove selected song/songs from the queue

