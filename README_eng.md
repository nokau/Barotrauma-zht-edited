# What is this?
This is a Traditional Chinese localization mod for the game Barotrauma, based on the official ones. Their lines are matched as close as possible with the game's current version English text files for easier side-by-side comparison.

Do use it at your own risk, as I couldn't guarantee any of the translations were as accurate as possible whatsoever, but feel free to edit it on your own. And always back up your edited files.

### I have something to report
Head over to the [Issues](https://github.com/nokau/Barotrauma.zht.edited.mod/issues) page, click on the green `New issue` button, then click the `Get started` button on the right side of the 2 issue types. And since this is a Traditional Chinese localization, please send your issues in Traditional Chinese.

### I want to contribute
I'm not familiar with GitHub or all its intended functions, to be honest, so if you're interested in doing so, I guess you could make separate versions of the project instead of changing the base files.

# For now this project focuses more on these elements:
- Names of the interactable items and devices
- Main menu UI
- Gameplay UI
- Partial Submarine Editor UI
- Names and descriptions of in-game interactable devices, items
- Events and missions
- NPC conversations

### Notes
- I left most of the character, location names within missions and events un-translated since all the generated names are not translated either.
- I left these ship names un-translated: Bunyip, Muikku, Selkie, Kastrull, Herja.
- Very different translated names for some of the items and devices.

# Project files
You can find the mentioned files inside this project's [current_version](./current_version) folder:
### NpcConversations_TraditionalChinese.xml
- This file contains edited lines of NPC conversations.
- The game's file is located at `Steam\steamapps\common\Barotrauma\Content\NPCConversations\TraditionalChinese`

### TraditionalChineseVanilla.xml
- This file contains edited lines of all the English files found within the game's Texts folder, because using seperated files doesn't seem to work.
- The game's file is located at `Steam\steamapps\common\Barotrauma\Content\Texts\TraditionalChinese`
- If you are interested in editing or comparing side-by-side with the English flies, there are 3 files in the project's folder that I use before combining them into TraditionalChineseVanilla.xml:
  - **TCVanilla.xml**
  - **TCVanillaEditorTexts.xml**
  - **TCVanillaNew.xml**

# Recommended Tools
- Notepad++
