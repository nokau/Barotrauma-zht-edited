# Barotrauma-zht-edited
[Barotrauma](https://store.steampowered.com/app/602960/Barotrauma/)

[This mod's Steam Workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=2804180128)

# What is this?
This is a Traditional Chinese localization mod for the game Barotrauma, based on the official ones. Their lines are matched as close as possible with the game's current version English text files for easier side-by-side comparison.

Use it at your own risk, as the editing is based solely on my own experience; I cannot guarantee that all edits are accurate, but feel free to edit it on your own. And always back up your edited files, or updates and game file verification would revert them to the official ones.

- ### I have something to report
Head over to the [Issues](https://github.com/nokau/Barotrauma.zht.edited.mod/issues) page, click on the green `New issue` button, then click the `Get started` button on the right side of the 2 issue types. And since this is a Traditional Chinese localization, please send your issues in Traditional Chinese.

- ### I want to contribute
I'm not familiar with GitHub or all its intended functions, to be honest, so if you're interested in doing so, I guess you could make separate versions of the project instead of changing the base files.

# For now this project had these elements edited
- Main menu UI
- Gameplay UI
- Partial Submarine Editor UI
- Names and descriptions of in-game interactable devices, items
- Events and missions
- NPC conversations

### Notes
- Very different translated names for some of the items and devices.
- The item parameters in Submarine Editor, as well as the components(Wifi, Sin, Cos, etc.) are still in English.
- Most of the character and location names within missions and events are un-translated since all the generated names have no translation either.
- These ship names are un-translated: Bunyip, Muikku, Selkie, Kastrull, Herja.

# Project files
You can find the mentioned files inside this project's [current_version](./current_version) folder:
### NpcConversations_TraditionalChinese.xml
- This file contains edited lines of NPC conversations.
- The game's file is located at `Steam\steamapps\common\Barotrauma\Content\NPCConversations\TraditionalChinese`

### TraditionalChineseVanilla.xml
- This file contains edited lines of all the English files found within the game's Texts folder, because using separated files doesn't seem to work.
- The game's file is located at `Steam\steamapps\common\Barotrauma\Content\Texts\TraditionalChinese`
- If you are interested in editing or comparing side-by-side with the English flies, there are 3 files in the project's folder that I use before combining them into TraditionalChineseVanilla.xml:
  - **TCVanilla.xml**
  - **TCVanillaEditorTexts.xml**
  - **TCVanillaNew.xml**

# Extra files
Inside this project's [current_version_extra](./current_version_extra) folder:

### TCVanillaEditorTexts.SP.xml
- This file is an edited version of TCVanillaEditorTexts.xml, one of the 3 files mentioned above; it contains translation to some of the item parameters that are editable in Submarine Editor or in-game. There are missing lines and overall not a complete edit.

# Recommended Tools
- Notepad++
