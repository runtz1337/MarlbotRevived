# *ᵐᵃʳˡᵇᵒᵗ ᵛ²*
                                                                                                                                    
                                                                                                                                                                                    
# MarlbotV2 now has a fix, you will need to toggle the *--clock* option on the GUI, otherwise the bot will not inject. Please refer to the issue log below.

# Overview:

This is a somewhat of a "re-release" of [Marl-Burrows](https://github.com/MarlBurroW) project, but he hasn't updated it in a while, nor is there a GitHub page for it anymore. The developer of this bot intended for it to be used in offline play, and strongly advises against online play due to the risk it poses. Which is why I have re-released this as others may want to take the risk themselves. This is an attempt to keep the bot itself public as that was what it was essentially intended for in the first place. I'm not going to sit and condone cheating, but I'm not going to gatekeep or infringe on your right to do what you want with your life which is why I'm leaving a guide and you can do as you wish. I do not take credit for the code itself, just some minor edits to allow it to work with new game patches, as well as purging some of the unneeded spaghetti code that others have added or is no longer needed to bypass certain functions. All bots will eventually outdate and lose their skill. (I.E. Seer was GC but is now Plat.) but if you have a little bit of Python knowledge, it's relatively easy to update/add new bots. I will leave a link to the source code which the amazing developer of this bot has left on an alt account on GitHub should you choose to go that route.


Source Code: https://github.com/LoveSexDrugz/RLMarlbot


# Cheat includes:

- *Nexto Build of Genesis* (personal favorite)
- *Carbon Free* (Nexto Build) (adapted since the original wasn’t fully compatible)
- *Original version of Nexto from the Git repository*
- *Element Bot v.1.6.0* (sorry, theres limited documentation on this bot but you're always welcome to do your own research!)
- *Necto (Nexto v1)* bit outdated but will still perform at a D2-C2 Level depending on user settings, ping, etc.
- *Seer* (old/deprecated) Used to be GC, is now maybe plat level. Worst bot of the seven and wouldn't reccommend unless you are toggling or are really trying to evade a ban.
- *NextMortal* (also a top contender to Nexto and Genesis, it's extremely powerful in some areas but lacks some newer mechanics.)



# Usage:



*Initialization*
- Launch your game.
- Turn off vSync and set your framerate to 120 FPS. 240/360 is second best if your eyes cannot handle 120. The change in bot performance is minor, but can become noticeable if you are using Seer or NextMortal.
- If using a lower end PC, please lower all graphics settings to the lowest to maintain a steady 120 FPS.
- Changing the resolution to 1080p may help, as the bot is trained at this resolution and the physics engine is tied to the graphics engine.


*Installation & Setup*
- Open the folder and click "RLOrbital.exe".
- In the GUI, Select your preferred bot using "Select Bot".
- Set your "Toggle Key" (this key will turn the bot on and off.) This can also be edited in config.json.
- Tick "SpeedFlip Kickoff" if using Carbon or NextMortal. (These two seem to have the kickoff issue, I haven't tested the other bots enough to confirm their kickoff, please play around with this setting as it can vary from bot to bot.)
- If you have BakkesMod installed/running, check the "BakkesMod" option. (CURRENTLY BROKEN ON SOME HARDWARE, IF IT WORKS, GREAT. PLEASE DO NOT EXPECT IT TO.)
- Click the "Find Processes" button and select the PID number that appears below.
- Hit "Start Bot".


*In-Game Usage*
- Once in-game, press your designated toggle key to activate the bot. (Note: You can inject or toggle the bot at anytime in the games process, launching, loading, etc.)
- Load into a game and observe the bot in action.
- Note: The bot might occasionally need to restart due to random failures. *(This bot will crash after a few hours. This is not meant to be "fully" afk, it will need some attention.)*
- Note: *This applies to people actively using the bot, not AFK'ing.* If the bot gets stuck (rare), toggle it off for a second and then back on. *(If you are afk'ing, the bot will automatically reset itself, if stuck, once a goal is scored, or the game ends, whichever occurs first.)*



# Updating:
To update offsets, go to the path you downloaded this repository at and delete "sdk_config.json" and then relaunch "RLOrbital.exe." This will automatically update the offsets. 


# Issue Log:
- 4.22.25 02:26:54 Genesis detection, do not inject (fixed on 1.6.0 and 1.6.0.1 now safe to inject.)
- 4.23.25 03:04:33 Injection broken, wait for fix. Bot will not inject. *(Fixed: toggle clock on GUI)*


# Support:
- https://discord.com/users/1276197937029976095
- www.instagram.com/runtz1337

This project showcases my slight programming skill (might as well call it skidding), problem-solving abilities, and interest in reverse engineering. It is not an endorsement of any illegal or unethical activities.
