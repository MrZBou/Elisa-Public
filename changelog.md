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

### 0.95b (most stable)

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
