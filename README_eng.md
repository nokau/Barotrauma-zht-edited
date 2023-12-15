# Barotrauma-zht-edited
[Barotrauma](https://store.steampowered.com/app/602960/Barotrauma/)

[This mod's Steam Workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=2804180128)

# What is this?
This is a Traditional Chinese localization mod for the video game Barotrauma, based on the official ones. Their lines are matched as close as possible with the game's current version English text files for easier side-by-side comparison.

Use it at your own risk, as the editing is based solely on my own experience and preference; I cannot guarantee that all edits are accurate, but feel free to edit it on your own. And always back up your edited files, or updates and game file verification would revert them to the official ones.

- ### I have something to report
Head over to the [Issues](https://github.com/nokau/Barotrauma.zht.edited.mod/issues) page, click on the green `New issue` button, then click the `Get started` button on the right side of the issue types. And since this is a Traditional Chinese localization, please send your issues in Traditional Chinese if possible.

- ### I want to contribute
GitHub doesn't allow direct editing unless a user is part of a repository. But users can create a `Fork` of an repository and send a `Pull request` after they make changes to their forked ones.

I'm not familiar with GitHub or all its intended functions, to be honest. Please refer to using the [Issues](https://github.com/nokau/Barotrauma.zht.edited.mod/issues) page if possible.

# For now this project has most of the texts edited, including:
- Main menu UI
- Gameplay UI
- Editor UIs
- Names and descriptions of devices, items
- Events and missions
- NPC conversations

### Notes
- For multiplayer, the game seems to require all players/host to have the same game/some mod files.
- Multiplayer texts like error messages, server managments, etc., might be way less complete/correct than other parts of the game.
- Name differences for some items and devices.
-	~~The item parameters in Submarine Editor, as well as the components(Wifi, Sin, Cos, etc.) are still in English.~~
    - Since game version v0.21.6.0, Editor UI and item parameters are now mostly translated.
- Component names (Wifi, Sin, Cos, etc.) are un-translated.
- Most of the character and location names within missions and events are un-translated since all the generated names have no translation either.
- These ship names are un-translated: Bunyip, Muikku, Selkie, Kastrull, Herja.

# Project files
Inside this project's [current_version](./current_version) folder, there are 5 files in total:

### NPC conversations:

Game file located at `Steam\steamapps\common\Barotrauma\Content\NPCConversations\TraditionalChinese`
- **NpcConversations_TraditionalChinese.xml**

### Other texts:

Game file located at `Steam\steamapps\common\Barotrauma\Content\Texts\TraditionalChinese`
- **TraditionalChineseVanilla.xml** - Gameplay UI, items, events, etc.
  - This file is a combination of ~Vanilla.xml and ~VanillaNew.xml
- **TraditionalChineseVanillaEditorTexts.xml** - Editor related items, UI, etc.
- **TraditionalChineseVanillaEndgame.xml** - Story related texts
- **TraditionalChineseVanillaFactions.xml** - Faction related texts

# Recommended Tools
- Notepad++
