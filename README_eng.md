# Barotrauma-zht-edited
[Barotrauma](https://store.steampowered.com/app/602960/Barotrauma/)

[This mod's Steam Workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=2804180128)

# What is this?
This is a Traditional Chinese localization mod for the video game Barotrauma, based on the official ones. Their lines are matched as close as possible with the game's current version English text files for easier side-by-side comparison.

Use it at your own risk, as the editing is based solely on my own experience and preference; I cannot guarantee that all edits are accurate, but feel free to edit it on your own. And always back up your edited files, or updates and game file verification would revert them to the official ones.

- ### I have something to report
Head over to the [Issues](https://github.com/nokau/Barotrauma.zht.edited.mod/issues) page, click on the green `New issue` button, then click the `Get started` button on the right side of the issue types. And since this is a Traditional Chinese localization, please send your issues in Traditional Chinese if possible.

- ### I want to contribute
I'm not familiar with GitHub or all its intended functions, to be honest, so if you're interested in doing so, I guess you could make separate versions of the project instead of changing the base files.

# For now this project has most of the texts edited, including:
- Main menu UI
- Gameplay UI
- Editor UIs
- Names and descriptions of devices, items
- Events and missions
- NPC conversations

### Notes
- Very different translations for some of the items and devices.
-	~~The item parameters in Submarine Editor, as well as the components(Wifi, Sin, Cos, etc.) are still in English.~~
- Since game version v0.21.6.0, the Editor UIs and item parameters are now translated.
- Component names (Wifi, Sin, Cos, etc.) are un-translated.
- Most of the character and location names within missions and events are un-translated since all the generated names have no translation either.
- These ship names are un-translated: Bunyip, Muikku, Selkie, Kastrull, Herja.

# Project files
Inside this project's [current_version](./current_version) folder:

There are 6 files

- **NpcConversations_TraditionalChinese.xml**
  - This file contains edited lines of NPC conversations.
  - The game's file is located at `Steam\steamapps\common\Barotrauma\Content\NPCConversations\TraditionalChinese`

- **TraditionalChineseVanilla.xml**
  - This file is EnglishVanilla.xml and EnglishVanillaNew.xml merged, containing events, item names, and such.
  - The game's file is located at `Steam\steamapps\common\Barotrauma\Content\Texts\TraditionalChinese`
- **TraditionalChineseVanillaEditorTexts.xml**
  - This file contains Editor related texts.
  - The game's file is located at `Steam\steamapps\common\Barotrauma\Content\Texts\TraditionalChinese`
- If you are interested in editing or comparing side-by-side with the English flies, in the same folder there are 3 files I use for editing:
  - **TCVanilla.xml**
  - **TCVanillaEditorTexts.xml**
  - **TCVanillaNew.xml**

# Recommended Tools
- Notepad++
