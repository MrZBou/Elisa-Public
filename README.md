# Elisa public repository
## Current version: 0.83b

This is the official repository of the discord bot 'Elisa'. In the ''Issues tab, you can leave an error message and I will definitely consider it. Thanks.

  ## Main commands

### Admins commands
More admin commands in 'settings commands'

- e!install - Install bot music interface the current channel [Only admins/DJ's can use this]

- e!DJrole [@role] - Gives this role the permission to full control of the bot [Only admins can use this]

- e!prefix [prefix] - Change bot prefix. If [prefix] is empty, then bot will display your current prefix (this command will also work with the 'e!' prefix, even if you change it)

- e!addrole [level] [@role] - Set role as a reward for get this level

- e!removerole [level] - Reset the role for getting this level

- e!roles - Get a message with data on levels and their roles
***
### Default commands

- e!help (e!ru_help for russian language) - Message with all bot commands with explanations

- e!user - Get some information about mentioned user
***
### Music interface commands

- e!uninstall - Uninstall music interface (the bot will accept this channel like any other)

- e!image [image URL] - Change background image for interface (shows when song queue is empty). Preferably use 'imgur' or 'yapx' **[only for admins/DJ's]**

- e!skipto [number] - Skip songs before to the selected

- e!remove [number] - Remove picked song from the queue

- e!last - Add last played song to the queue

- e!vol [volume%] - Sets the music volume

Playlists commands

- e!pl_add [num / num1-num2] - Add selected songs from song queue to playlist

- e!pl_get [@user] - Get your playlist, or playlist of mentioned user (if him playlist is public)

- e!pl_play [num / num1-num2] - Add song/songs of playlist to the song queue (if you haven’t specified a number, the full playlist will added to queue)

- e!pl_private - Set your playlist private/public

- e!pl_remove [num / num1-num2] - Remove selected song/songs from the queue

