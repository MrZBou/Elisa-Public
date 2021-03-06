## 2.0 [01.11.2020]

- Release

#### 1.7.3 [22.10.2020, Fix Update]

- Fixed a bug due to which Elisa gave a privacy error for almost all of your requests

#### 1.7.2 [20.10.2020, Fix Update]

- Bug: item time get less than 0

- Bug: battle command didn't work

- Added some debugs to fix bugs in 1.8

#### 1.7.1 [02.10.2020]

- 'welcome' command
- * reset the image with the command 'welcome image reset'
- * now the image is in embed (color of embed changing by 'color' command)
- * support special args. Args stores in 'welcome args'. For example - 'welcome text Hello, [mention]! Nice to meet you on server [server_name]'. You can test message using 'welcome test' command. 

- fixed bug with 'battle' command

- fixed bug when Elisa did not send the error with adding the song

### 1.7 [October Update, 2020]

__Features__

- #### Inventory system! Store and use various items. 
- ##### * Items help in improving statistics, as well as in some other details (for example, increasing the volume of the music even more). 
- ##### * Actions with items - Sold, pick (in the case of backgrounds), and also used.
- ##### * 'item' command to get information about item by item ID
- ##### * An exclusive background "elisa_bg" was added to all users for using Elisa
***
- 'gift' command.
- * Getting a good prize, money, experience, or item
- * There is a chance of getting nothing, there is also a chance of a jackpot
- * Can be opened no more than 1 time per day. At 00:00 UTC. the counter is reset
- * So far, the only way to get items
***
- 'rank' command.
- * User card with his statistics. The level and XP, the bar of getting next level, the amount of money and money on the deposit, as well as the position in the top money and level are displayed. The amount of items in the inventory is also shown.
- * The card is made in the form of a JPG picture, so it looks more beautiful than a regular embed
- * You can change the background if you have the required item in your inventory
- * The alias of the 'rank' command is 'level'. (previously 'rank' was an alias for the 'user' command)
***
- 'welcome' system.
- * Allows you to send special messages to everyone who just got to your server.
- * 'welcome enable' - Enable system, 'welcome disable' - Disable system, 'welcome text' - Change text of message, 'welcome channel' - Change the channel to which the message will be sent, 'welcome image' - Change image of message (image URL), 'welcome test' - Test welcome message on current channel
***
- New database for leveling/economy. Commands executes is now faster and has fewer bugs.

- You can now add temporary items to the store. For example, if the item time is 3 hours, then the member who bought this role will lose it after 3 hours

__Little changes__

- 'ignore' command was removed

- 'exp' term changed to 'XP'

- Instead of mentioning a person in the team, now you can write his nickname or ID (mentioning is still the best option)

- 'user' command no longer shows statistics

- 'user' command instead of all the roles of a person now shows his highest rights

- 'shop add' now creates items with a 5-digit code of letters and numbers. Previously, the code was only numbers.

- Adjusted the values required to get a new level

__Bug Fixes__

- DM's now always send full messages of leveling up. Previously, they were short at the enabled 12th setting.

- Elisa's green talk icon now works correctly

- Fix bug, when shuffled queue loop could not be stopped with the stop button

- Translation bug fixes.

***
***

#### 1.6.3 [update 15.09.2020]

- 'luck' command. You can set a bet and with an equal chance, you will either double it or lose it (be careful).

- 'leveling' settings disables all economy/leveling commands.

- Fix bug with russian translation for all messages.

- 'shop' fully supported russian language

#### 1.6.2 [update 12.09.2020]

__Features__

- #### Deposit system. Stores money and increases its amount over time. Does not interact with the server treasury in any way. You can put your money to deposit using 'deposit add <amount>' and take with command 'deposit take <amount>'
  
- 'reset all' command resets all user statistics [level, exp, money, deposit] on the server

__Bug fix__

- Simplified connection system. By fact, this only fixes most of the possible bugs and errors associated with music.

- Role manager did not work in a 1.6.1 ver.

- After a kick from the server, Elisa will delete all data associated with server.

#### 1.6.1 [update 4.09.2020]

__Using__

- #### Full russian translation. Almost all text is now translated if the guild region is Russia.

- The interface now shows the count of views on the video.

- The amount of money in the treasury is displayed more beautifully if it is more than 1K or 1M

- Interface design get some changes.

__Bug fixes__

- 'shop buy' command now work correctly

- 'top' command now work correctly

- Some messages might not be sent into channel

- Fixed bug when bot get stopped

### 1.6 [update 23.08.2020]

__Economy / Leveling__

- ##### Treasury system. For each transfer between users, the treasury will receive a commission from the transfers (default - 3%). You can change the amount of the commission, take money from the treasury, distribute it for specific roles, and donate your money in the treasury. (command - "treasury")

- Experience is now given for being in the voice channel, and small amounts of money come to the treasury. If Elisa's music is playing in the channel, then the received reward increases.

- The maximum level for "level" command has been increased to 150 (was 100)

- Fixed bugs with the systems

__Music__

- If the channel in which Elisa is playing music is empty, then you can request music from any other channel, and Elisa will connect to this channel and completely clear the music queue. This option can be disabled in the settings.

- Connecting to full voice channels (only with administrator permissions)

- The repeating track is no longer accompanied by an audio initialization message.

- Changed audio equalizer settings

- You can change the picture ("image") even if music is playing now

- The 'skipto' and 'skipfrom' commands now work correctly

__Using__

- The mention of Elisa at the beginning of the message denoted as a prefix. (helps if you forgot it)

- Added 12 settings to make all Elisa messages shorter.

- Fixed many bugs

***

#### 1.5.3 [update 10.08.2020] [+hotfix 11.08.2020]

- You can specific videos from playlists by index at the end of url (&index=)

- Fixed all bugs with 'top' and 'top g' commands

- Upgrade messages are deleted after timeout if they were sent to the music channel

- Rewritten old interface code, now there will be fewer errors with it. Also, if nothing is playing, the status will be an emoji ⏹️, and when the music is playing, the channel name will be shown at the topю

- Changed the settings command and now it is much easier to use it

- Added 2 new options in settings. 1 - Hide the names of private channels while playing music in them, 2 - Don't show time bar

- Upon reaching a new level, if a role is attached to it, then the message will be written about it

- 'battle' funny command. The bottom line is choosing the actions that will bring you victory. You have a limited money for which you must purchase the necessary items. Then try to kill your opponent using these items.

#### 1.5.2 [update 06.08.2020]

- Elisa now gives roles as levels by id. That is, you can change the name of the role that receiving for a level, and Elisa can find and give that role.

- Added messages for 'addrole' and 'removerole' commands, in case of lack of permissions, Elisa will notify you

- 'roles' command changes to 'levels', and now shows id of the role.

- Added a GIF that shows how to use Elisa's music for those trying to use the 'play' command

- Fixed bug with 'prefix' command.

- Fixed other minor issues.

#### 1.5.1 [update 05.08.2020]

- Fixed bug with video requesting via url

- Fixed bug due to which Elisa could not play music in a full voice channel.

- Fixed bug where Elisa could restart for no apparent reason (processing)

- Fixed bugs with 'pl list'. With that you can play playlists not only by their userid, but also by position in 'pl list'

- Fixed a bug due to which the requester of a track from the playlist was the one who last added it to his playlist

- Added commands 'skipfrom' and 'skipfromto' for better interact with a queue

- New option (in 'settings' command) to send messages of level up to DM's / text channel

- 'ping' command shows the uptime and current working Elisa's version

### 1.5 [update 01.08.2020]

- Added the opportunity to loop the queue of tracks, and adding a queue to your playlist. Added 'loop' command to manage repeating queue.

- Fixed translation problems.

- Improved sound quality, also live streams do not laggy

- The title of the playing song now has a link where you can go to the original video

- Added playing attached mp3 files. The message sented with this file will become its title.

- The volume can now be set in the range from 5-200% (old: 30-200)

- Added the 'clean' command, which removes unnecessary messages in the music channel.

- After installing a music channel, you can go to it through the channel mention.

- Queue size increased to 100 tracks.

- When Elisa added to the server, she will send a message using a channel convenient for her.

- Removed 'autoleave', 'autoclear', 'notifications', 'levels' commands. All available settings are in the 'settings' command. Some options have also been added.

- The statistic system now works for each server separately. After the update, the first server where you send some message will receive these statistics, on the other servers your stat's will be cleaned. Also 'top' command shows the best on the current server, and 'top g' shows the best of all users.

- 'pl list' is now multiple pages and sorted by the amount of tracks in the playlist

- Added 'ping' command

- URL's now plays correctly

- Other small changes that make using Elisa better.

- Fixed many bugs.

Thanks to all users, with you all I finally got Elisa's verification, I am very happy to continue make updates for you!)

#### 1.4.4 [update 12.07.2020]

- Changed player, now Elisa will work more stable and will not turn off for few hours

#### 1.4.3 [update 21.06.2020]

- Health system improved

- Fix bug, when time bar of repeated song be laggy

- Fix song titles in queue (when one " in title can coloring all queue)

- Update modules

#### 1.4.2 [update 05.06.2020]

- Optimized code

- Health system with 'health' command [funny commands]

- shop add, shop remove, etc. may be using with no space

#### 1.4.1 [update 02.06.2020]

- fix bug when songs titles cuts forever, if song queue size exceeds 30

- 'removerole' wasn't working

- 'image' command now supports attached images

- 'djrole' & 'manager' commands now not avaliable in music channel

### 1.4

- Update music player visual's

- You can set volume between 30% - 200% (before - 50% - 150%)

- Song queue size upped to 61 songs

- 'status' command to check enought permissions

- New Elisa's avatar :D

- Bug fixes

### 1.3

- New host and much better audio quality

- Improve the leveling/money system

- Added 'top' command. Shows the highest levels from all servers where Elisa is located

- Russian translate was improved

- Fix bugs in shop system

- Fix many bugs

### 1.2

- Now Managers fully controlling the Elisa, except for set the manager role

- By default in created music channel (when using e!install), everyone can be read and send messages

- Fixed music search system. Now, by URL, a song can be found with almost 100% probability

- Now live streams playing correctly

- Changed default color and backgroun embed image

- Added the 'all' property to playlist options. For example, you can play all songs from a playlist by writing **e!pl play all**. This workyly with **e!pl remove** and **e!pl add**

- Improve russian translate

- Bug fixes

### 1.1

- 'install' comand install music UI in special channel

- Bots messages will now be deleted in the music channel

- Translate to russian language, if guild region - Russia (not finished)

- 'leave' command

- Bug fixes

## 1.0 (testing)

- Redesigned music system. Now the errors is minimized

- 'ignore' command to ignore prefixes in voice channel (for example, if you like p!catch in the music channel)

- Shoping system. You can sell roles for the cash you receive for messages. They were previously useless.

- 'bal' command to check your current balance

- You can reset embed image using 'image reset'

- 'user/rank' refined, now there is more information

- Manager role system. Users with the manager role will be able to circumvent the limitations of the music system. For example, using UI reaction, not being in the channel with the bot.

- Fix many bugs

### 0.95b

- Upgrade 'user' command. And if you disable the level system on the server, then it and cash will not be displayed in the user information

- Add funny commands with different outcomes :) - 'wink', 'spit', 'punch', 'kill'/'shot'

- Fix music bugs, when bot may be restarted while playing music (not finally :C)

- You can check/sets/removes DJrole in music channel too. Yeay.

- Add 'color' command to change embed color. Working in music channel too. Support red, blue, green, yellow, orange, white-blue, gray, black, dark, pink, maroon, lime, purple colors.

- Pay command be improved. Now the message always looks right and changes depending on the amount sent. You can also swap the mention and amount (e!pay 5 @zbou, e!pay @zbou 5 be working too)

#### I would be very glad for your suggestions for updating in our support server - [Elisa Supporting discord server](https://discord.gg/MRwhjHP)

### 0.93b

- Embeds instead default messages

- Fix bugs that stopped the bot

### 0.92b 

- You can set 3 DJ roles, instead of one

- More notifications

- 'pl list' command to get users playlists list

- Bug fixes

### 0.91b

- Add 'kiss' and 'hug' commands (the most important thing in update)

- Add 'move' and 'replace' commands in music channel for more convenient interaction with music

- Add 'pay' to paid money to other peoples (money so far useless)

- Some changes to improve usability. For example: now you can put a space after the prefix

- Now the bot will be notify you of a possible restart, as well as other things

## 0.9b

- Serious bugs fixed (for example, when all users’ playlists were deleted for an unknown reason)

- Some commands received synonyms (for example, e!help - e!commands) for convenience

- Fix bugs, which appeared due to the use of a large number of users

- Update 'help' command

- Now the bot will request permissions only when necessary, and only if you got an admin permission

- Optimize updating system, now bot will save all necessary information before reloading

- Now you can get information and play other people's playlists by adding his id or mention at the end of the message

- Add 'levels' command to enabling/disabling levels system (with roles) on this channel

### 0.84b

- Fixes many bugs

- Improve the music searching system. 

- Now only DJ's and admins can interact with music, but if DJ role not specified, everyone will can interacting.

### 0.83b

- Some bug fixes

- Removes volume reactions (⬆️ & ⬇️)

- Add 'vol' command (changes volume, 50 - 150 %)

- Add shuffle reaction (🔀). After clicked, all songs in the queue are mixed

- Bot can work without all the necessary permissions, but without some features

### 0.82b

- Add 'Status' field to music interface

- Add 'Request by' field to music interface (if add song to playlist, this user will be requester)

- Increased security

- Bug fixes

### 0.8a

- Fix problems with permissions

- Add 'uninstall' command

- Add 'notification' command

- Bot will playing music wherever can speak

- Fix messages problems

- Change embed pictures


#### older bot versions was not be outlined
-----
