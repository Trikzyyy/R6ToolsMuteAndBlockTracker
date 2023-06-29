Trikzy Block Bot V1 README.TXT

############################################
EN   -    Every feedback are good to take, good or not. For it contact me on twitter > @TrikzyR6 - Follow to see the new update on the app
############################################

You must update Profiles.JSON (open in notepad if you dont have anything else) in the Profiles folder, !!!DO NOT MOVE THE FOLDER
Only change the second part wich is for exemple "your mail"  !!!DONT CHANGE THE "email","mdp","url2","lang" OR IT WILL NOT WORK
For the discord webhook link > Create a discord server (or use one you already created/own) >  Server Settings > Integrations > Webhooks
>New Webhook > Choose the channel you want and copy the link, paste it on the "your discord webhook" part 
For the bind_pseudo_tracker parts, it's the bind you'll choose for the search by name functions, wich mean it's only one bind and not in caps (to be aware of possible bug)
This bind will be usefull, and dont choose a bind that you'll hit so much, since it's activating the functions even is the .exe is hide (if your on r6 game page tho)
If you dont want this function, put nothing between the " > wich would look like "bind_pseudo_tracker":""
Same for the bind_mute, but this one will allow you to Mute/Unmute R6 just by pressing a bind, wich is really usefull for prep phase
Do not hold any of those 2 bind, that will open so many page and will make crash everything
There is a security for 1 sec hold

############################################
DO NOT START THE APP MORE THAN 5 TIMES IN 10 MIN, EACH TIME YOU START IT WILL CONNECT TO YOUR UBISOFT ACC, IF THERE ARE TOO MANY CONNECTION AT THE SAME TIME IT WILL BE BLOCK TEMPORARLY (10 MIN)
Start TrikzyBlockStatsTrackerV1.0.exe  (main app)
HOW IT WORK :
When you block someone with the ubisoft account you entered, the discord webhook bot will send you all the stat needed in the channel you choosed
All the stats are in ranked only, except if the account has never played ranked in this season, his actual casual stats will be shown (kd, k/m) 
Press the bind you chosed for the other options
For every question you have > dm twitter : @TrikzyR6
If the app doesn't respond, it means an error occured, if you find why it's happening, tell me on twitter so i can fix it
When it happens, just restart the app
For any recommends or bug correct (and also english mistake, i'm french so if there are some mistakes, tell me) > dm twitter : @TrikzyR6

If you want to put the app on you're desktop without all the other files, just create a shortcut (right click) 

TrikzyPseudoTracker.exe :
Alt app that i added for the "Search by name" function on the main app (TrikzyBlockStatsTracker).
You can also use it without the main one, if you want to find someone stats with his name.
Theres no interface on it since its supposed to work with main app.
If it close after a search, that mean the name don't exist or stats are 0, i got error case but it might bug, if it do, dm me with the name that you wrote and what's the app returns you

Autostart: 
This will allow you to open the .exe automaticaly once you start R6, check AUTOSTART.txt for more info about it.

svcl : 
Its the .exe i use for the mute R6 fonctionnality, you don't need to start it to use this fonctionnality, just let it here

Switch :
It's the .bat i'm using to mute the game, if you start it manually,it'll mute/unmute the game

