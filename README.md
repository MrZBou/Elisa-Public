# Elisa public repository
## Current version: 1.4.2
This is the official repository of the discord bot 'Elisa'.

> Invite link - https://discordapp.com/oauth2/authorize?client_id=696934742876225566&scope=bot&permissions=271641616

> Support server invite - https://discord.gg/MRwhjHP

  ## Main commands
>> __Square brackets ( [] ) are used to indicate the value you must type. When using the command, *you do not need to write them*! For example: e!DJrole [@role], you should type e!DJrole @DJ__

### Admins commands
More admin commands in 'settings commands'

- e!install - Install bot music interface the current channel [Only admins/DJ's can use this]

- e!shop add [@role] [cost] [description] - Add role to the store

- e!shop remove [code/role-position] - Remove role from the store

- e!djrole [@role] - Gives this role the permission to full control of the bot (max DJ roles: 3) [Only admins can use this]

- e!manager [@role] - Set the manager role. Managers can control the music without even being in the music voice channel.

- e!prefix [prefix] - Change bot prefix. If [prefix] is empty, then bot will display your current prefix (this command will also work with the 'e!' prefix, even if you change it)

- e!addrole [level] [@role] - Set role as a reward for get this level

- e!removerole [level] - Reset the role for getting this level

- e!roles - Get a message with data on levels and their roles (in DM)

- e!autoclear - Disabling/enabling clearing old roles, gotten from level up's, when you reach a new level role (default: enabled)

- e!notifications - Disabling/enabling bot notifications (level up, music initialize) (default: enabled)

- e!levels [enable/disable] - Enabling/disabling levels-roles system on this channel (default: enabled)

- e!reset settings - Set the default settings for the bot (like when you added she to the server)
***
### Default commands

- e!top [levels/money] - Top users in this category (type just e!top to get full information)

- e!shop - Roles store on this server (e!shop list - smallest version)

- e!shop buy - Buy item from store

- e!help - Message with all bot commands with explanations

- e!user - Get some information about mentioned user

- e!pay [amount] [@user / userid] - Transfer money to another user (money displayed in e!user)

- e!bal - Check your current balance

- e!status - Elisa's permissions status

Funny commands

- e!kiss [@user] - Kiss the user (who would have thought?)

- e!hug [@user] - Hug the user

- e!spit [@user] - Spit to user

- e!punch [@user] - Punch the user

- e!kill [@user] - Kill the user (cruel, but fair)

- e!health [@user] - Health of user
***
### Music interface commands

- e!ignore - Current ignored prefixes in music channel

- e!ignore [prefix] - Ignore messages with this prefix in music channel **[only for admins]**

- e!ignore clear - Clear ignored prefixes list **[only for admins]**

- e!uninstall - Uninstall music interface (Elisa will accept this channel like any other) **[only for admins]**

- e!image [image URL] - Change background image for interface (shows when song queue is empty). Preferably use 'imgur' or 'yapx'. You can reset image using 'e!image reset' **[only for admins]**

- e!color [color name] - Change inteface strip color **[only for admins]**

- e!skip - Skip current song (instead of this command i recommend using ⏭️ button in UI)

- e!stop - Clear the song queue (instead of this command i recommend using ⏹️ button in UI)

- e!autoleave - Disabling/Enabling auto leave from voice channel, when song queue is empty (default: disabled)

- e!skipto [number] - Skip songs before to the selected

- e!remove [number / number1 number2 ...] - Remove picked song / songs from the queue

- e!last - Add last played song to the queue

- e!vol [volume%] - Sets the music volume

- e!move [song1] [song2] - Move the song1 to song2 place in queue

- e!replace [song1] [song2] - Replace the song1 to song2

Playlists commands

- e!pl help - Help with playlists commands

- e!pl add [num / num1-num2] - Add selected songs from song queue to playlist

- e!pl get [@user] - Get your playlist, or playlist of mentioned user (in DM)

- e!pl play [num / num1-num2] [@user] - Add song/songs of playlist to the song queue (if you haven’t specified a number, the full playlist will added to queue, and if you don't pick a user, your playlist will be playing)

- e!pl private - Set your playlist private/public

- e!pl remove [num / num1-num2] - Remove selected song/songs from the queue

- e!pl list - Get a full list of user's playlists (in DM)

