## Notes
Added quests and npc's from the database, some info is wrong and some quests and npc's are missing. I skipped the quests descriptions.

Missing quests [here](https://github.com/Khiu/TurtleWoW/blob/main/skippedquests.txt)  
Missing npc's [here](https://github.com/Khiu/TurtleWoW/blob/main/npcWithoutCoords.txt) and [here](https://github.com/Khiu/TurtleWoW/blob/main/npcZoneZero.txt)

# pfQuest (turtle)
This AddOn is a [pfQuest](https://github.com/shagu/pfQuest) extension, which adds support for the [TurtleWoW](https://turtle-wow.org/) Private Server. In order to run this extension, the latest version of [pfQuest](https://github.com/shagu/pfQuest) is always required and only enUS-Gameclients are supported.

*Notice: Issues and bugs like "please add quest XYZ" and all other content requests will be silently ignored.*

If you wish to add more content, feel free to contribute and send [Pull Requests](https://github.com/shagu/pfQuest-turtle/pulls).

## Install
1. Download **[Latest Version](https://github.com/shagu/pfQuest-turtle/archive/master.zip)**
2. Unpack the Zip file
3. Rename the folder "pfQuest-turtle-master" to "pfQuest-turtle"
4. Copy "pfQuest-turtle" into Wow-Directory\Interface\AddOns
5. Restart Wow

## Contribute
This project always needs **your** help: If you find a quest that doesn't work for you, please consider looking it up, adding it, and then create a pull request towards this repository. The database format in use, is similar to the pfQuest databases. It uses the same table patching mechanism as in the "pfQuest-tbc" database.

A basic example how things get added, modified and removed can be seen in the commit ([db: add shagu and his quest chain](https://github.com/shagu/pfQuest-turtle/commit/081f48076a9f0a3b44f784d7b8221931986c6af6)), which adds the [Shagu](https://database.turtle-wow.org/?npc=60300) NPC with his [Puffing Peace](https://database.turtle-wow.org/?quest=40001) quest-chain.

### Pending Quest List
https://docs.google.com/spreadsheets/d/1-DYHaEq8GD8lH10GJXZxD9iNLNWjl4XA32u_Ire11NY/edit?usp=sharing
