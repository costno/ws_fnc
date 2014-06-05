ws_fnc for ArmA2:CO and ArmA3
==
Wolfenswan [FA]: wolfenswanarps@gmail.com | folkarps.com
Last update: 31.05.14

**INTRODUCTION**

This is a collection of various functions that I wrote and am writing for my Arma 3 missions.
None of them are revolutionary but all of them have been designed with efficiency and performance in mind.
The idea is to reduce the need for repetitive scripting as much as possible while avoiding the need for third-party scripts and the problems that come with that. 
I've also tried and comment everything as best as possible to make understanding the code easier.



**SETUP**

Unzip the archive to your mission root folder and rename the folder ws-fnc-master to ws-fnc. You should now have a ws_fnc folder with various subfolders inside.

ArmA 2:
* [] call compile preProcessFile "ws_fnc\ws_fnc_init.sqf" from unit or module init field.
* You can safely delete the description.ext that is inside ws_fnc\

ArmA 3:
* If your mission does not have a description.ext you can move the description.ext from ws_fnc\ to your mission root folder.
* If your mission does have a description.ext open the descripion.ext inside ws_fnc\ and paste the code within the cfgFunctions scope at the bottom of your own description.ext. If the cfgFunctions scope does not exist yet, simply copy the entire scope to the bottom of your description.ext.
* If you are using F3 see this post for an example: http://www.folkarps.com/forum/viewtopic.php?f=48&t=785#p4792



**DOCUMENTATION**

* All major functions are documented in themselves. To see how they work open their .sqf with a text editor or their pages on github. 
* If you're running ArmA 3 then you can also seem them all in the editor when opening the function viewer (CTRL+F). Make sure to select "missionConfigFile" in the top-left drop-down menu.
