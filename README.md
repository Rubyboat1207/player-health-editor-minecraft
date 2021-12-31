# player-health-editor-minecraft
A Minecraft data pack that edits player health.

** I have left the readme the same as it was before but please not that this does not work for any versions older than 1.17

# 1.18+ #
**Note: This data pack is in beta, and is in the works.  If you have any bugs please let me know, and I'll add it to the known bugs list.  Also, this is not tested in any version other then 1.18.1**

I created a data pack that allows you to set health and  deal damage to a player(for mobs use data modify instead).  First off, you can get the data pack <a href="https://github.com/randomuser922/player-health-editor-minecraft" title="Data pack download link">here</a>.  After installing it, make sure it says in chat that it was installed.
# How To Use #
**Dealing Damage**

To damage a player, set that player's `damage` scoreboard to how much damage you want to apply(negatives heal players), then run the function `editor:deal_damage` as the player you want to damage and you are done.

**Setting Health**

To set the health of a player, set that player's `sethealth` scoreboard to what health you want that player to have, then run the function `editor:set_health` as the player you want to edit health and you are done.

**Remember: 1 heart is 2 HP, and a half a heart is 1 HP, default max health is 20 HP(10 hearts)**

**The Commands**

To damage players:

    scoreboard players set <selector> damage <value>
    execute as <selector> run function editor:deal_damage

To set player health:

    scoreboard players set <selector> sethealth <value>
    execute as <selector> run function editor:set_health


# How It Works #

What the data pack does is set the max health of the player to what health you want to set, and gives the player the instant health effect so it will update the player health, setting the player's health to max, then it sets the max health to be what it originally was.
# Known Bugs #
* A bug that shows the player as dead, even though they are not. (Its a Minecraft bug)
* A bug that ignores absorption hearts, and skips to the base hearts.
# Incompatibilities #
**All Incompatibilities are being worked on to be compatible**

* An existing helmet/item in the helmet slot with the max health attribute

# Finding Bugs/Issues #
**Bugs**

If you find any bugs, please report it.  Also add how you found the bug, so I can recreate it, and fix it, videos/screenshots of bugs are preferred.

**Issues**

If you have any performance issues while running the data pack, please report it.  Also add what performance issues you are getting, low tps, low fps, etc.  Videos/screenshots and computer specs do help!

**Where to report**

To report bugs/issues, use the issues page on the GitHub download link.

# Terms of Use #
**Note:** This section is subject to change, and you are held responsible for checking back regularly.
If you use this in a data pack to publish, you must put the GitHub link to the data pack somewhere for others who may want it, and cannot sell and/or use for your financial benefit unless given explicit permission.  You are welcome to edit the data pack to whatever you want, just don't break it!  If you wish to get explicit permission for anything, please email me at contact.ezmc@gmail.com and I will consider your case.

# Support #

For anything about bugs/issues see the Finding Bugs/Issues section.

For any questions or suggestions, please email me at contact.ezmc@gmail.com and I will respond as quickly as possible.

