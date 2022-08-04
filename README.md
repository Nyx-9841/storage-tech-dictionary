# Storage Tech Dictionary
## Table of Contents
[Information](https://github.com/CommanderGenesis/storage-tech-dictionary/edit/main/README.md#information)  
[Dictionary](https://github.com/CommanderGenesis/storage-tech-dictionary/edit/main/README.md#dictionary)  

## Information
The storage tech dictionary is a compilation originally created by boyenn (boyenn#3717) and Firigion (Firigion#7498), and ported to GitHub by me, CommanderGenesis (CommanderGenesis#5623) to accompany the storage tech Discord server (https://discord.gg/JufJ6uf). It is meant to be a rough glossary of storage tech terms, features, contraptions, and bad practices to explain commonly used vocabulary within the storage tech community, as well as a resource for useful data to assist your research or simply feed your general knowledge. It is highly recommended that new members of the storage tech community read this dictionary in its entirety, to fully understand the terms used in the Discord. To request that a new definition or resource be added to the dictionary, simply create an issue in the issues tab. Do not create a pull request, as those will likely not be monitored. For help, questions, or concerns, please contact one of the dictionary curators on the storage tech Discord server.

## Dictionary
| Name | Tags | Definition |
| ------------- | ------------- | -------------|
| aligner | term | aligns items within a block to ensure some sort of behavior. More basic concepts involve simply letting items in a water or ice stream hit against a block with a certain hitbox, while more complex ones involve precisely timed contraptions (see perfect aligner/4D alignment). The more simple usecases involve using a chest, dragon egg, 2 or 3 stack of pickles, cake or some other block to align the items between two blocks such that they go over some hoppers and are inside a water stream at the same time. The use of different hitboxes allows for some more complex behaviour, where items can cycle exactly twice in a loop and then exit, or you can send many channels along one water line and have each channel exit in a different spot of the stream. |
| batcher | contraption | groups item entities together before periodically releasing them into a waterstream or iceline. This is done to improve lag and because some filters (especially 2x filters) would be on cooldown much less often and therefore miss less or no items. |
