# Elisa public repository
## Current version: 2.1
This is the official repository of the discord bot 'Elisa'.

> Invite link - https://discordapp.com/oauth2/authorize?client_id=696934742876225566&scope=bot&permissions=8

> Elisa's discord server - https://discord.gg/MRwhjHP

  ## Main commands
>> __Square brackets ( [], <> ) are used to indicate the value you must type. When using the command, *you do not need to write them*! For example: e!DJrole [@role], you should type e!DJrole @DJ__


### <> - required, [] - optional


### Admins commands

- e!install - Install bot music interface the current channel

- e!welcome [enable/disable/text/channel/image/test] - System of welcome new server members

- e!giverole [time in minutes] <@member> <@role> - Give role to a member

- e!cp - Create a voice channel controlling panel

- e!clear [time in hours] <amount of messages> - Clear messages in current text channel

- e!shop add <@role> <cost> [description] - Add role to the store

- e!shop remove <code/role-position> - Remove role from the store

- e!treasury [add/take/percent/award] [amount] [@role for "award"] - Treasury system.

- e!dj [@role] - Gives this role the permission to full control of the bot (max DJ roles: 3)

- e!manager [@role] - Set the manager role. Managers can control the music without even being in the music voice channel.

- e!prefix [prefix] - Change bot prefix. If [prefix] is empty, then bot will display your current prefix (this command will also work with the 'e!' prefix, even if you change it)

- e!color <color name> - Change inteface strip color

- e!levels [add/remove/clear/help] - Leveling roles integration

- e!levels message [title/text/channel/test/args] - Level up message settings

- e!settings [option number] [0/1] - Elisa's settings

- e!reset all - Remove all data and settings of Elisa (includes leveling/economy data of every server's member)
***
### Default commands

- e!inv [use / pick / sell] [item number / item_id] - Inventory system

- e!item <item_id> - Get information about item.

- e!category <category_id> - Get information about category

- e!ping - Shows delays as well as upTime and current version of Elisa

- e!top - Top users in this category (type just e!top to get full information)

- e!shop - Roles store on this server (e!shop list - smallest version)  |  e!shop buy <item code> - Buy item from store

- e!help - Message with all bot commands with explanations

- e!commands - Full list of commands

- e!user [@member] - Get some information about mentioned user, or about yourself

- e!rank [@member] - Card with statictics of user

- e!trade <@member> - Trade with user (items/money)

- e!pay <amount> <@member / userid> - Transfer money to another user (money displayed in e!user)

- e!bal [@member] - Check your current balance

- e!luck <amount> - Double or lose the billed money
  
- e!gift - Open gift with nice things! Only once a day.

- e!dep [add/take] [amount] - Deposit system. Stores money and increases its amount over time (default - 0.01% per minute). Does not interact with the server treasury.

- e!job - Your job stat card

- e!work - Start working / Complete job mini-game

- e!case [buy/info] - Case store

- e!collection [make] <collection_id> - Information about collection / Combine a collection to collectible item

- e!status - Elisa's permissions status

Arcade commands

- e!battle <@member> - Battle with user

- e!kill [@member] - Kill the user (cruel, but fair)

- e!health [@member] - Health of user

- e!kiss [@member] - Kiss the user

- e!hug [@member] - Hug the user

- e!spit [@member] - Spit to user

***
### Music interface commands

- e!uninstall - Uninstall music interface (Elisa will accept this channel like any other) **[only for admins]**

- e!image <image URL / attached file / 'reset'> - Change background image for interface (shows when song queue is empty). Preferably use 'imgur' or 'yapx'. **[only for admins]**

- e!color <color name> - Change inteface strip color **[only for admins]**

- e!skip - Skip current track (instead of this command i recommend using ⏭️ button in UI)

- e!stop - Clear the track queue (instead of this command i recommend using ⏹️ button in UI)

- e!skipto <number> - Skip tracks before to the selected
  
- e!skipfrom <number> - Skip all tracks counting from the specified
  
- e!skipfromto <number> - Skip tracks in the specified range

- e!remove <number / number1 number2 ...] - Remove picked song / songs from the queue

- e!last - Add last played song to the queue

- e!vol <volume%> - Sets the music volume

- e!move <song1> <song2> - Move the song1 to song2 place in queue

- e!replace [song1] [song2] - Replace the song1 to song2

- e!clean - clear music channel from not necessary messages

- e!loop ['add'/'remove'/'clear'] [song position] - Manage queue loop

Playlists commands

- e!pl help - Help with playlists commands

- e!pl add <num / num1-num2> - Add selected songs from song queue to playlist

- e!pl get [@member / userid] - Get your playlist, or playlist of mentioned user (in DM).

- e!pl play [num / num1-num2 / n + position in 'pl list'] [@member / userid] - Add song/songs of playlist to the song queue (if you haven’t specified a number, the full playlist will added to queue, and if you don't pick a user, your playlist will be playing). Also you can get playlist by position of playlist in 'pl list'. Example: 'pl play n7'

- e!pl private - Set your playlist private/public

- e!pl remove <num / num1-num2> - Remove selected song/songs from the queue

- e!pl list [page] - Get a full list of user's playlists (in DM)

