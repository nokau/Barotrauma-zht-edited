# Barotrauma-zht-edited
[Barotrauma on Steam](https://store.steampowered.com/app/602960/Barotrauma/) | [繁體中文README](./README.md) | [This mod's Steam Workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=2804180128)

# What is this?
This is a Traditional Chinese localization mod for the video game Barotrauma, based on the official ones. Their lines are matched as close as possible with the game's current version English text files for easier side-by-side comparison.

Use it at your own risk, as the editing is based solely on my own experience and preference; I cannot guarantee that all edits are accurate.

Repo history is a big mess; I'm unfamiliar with version control concept and all the GitHub functions.

### Report issues
Head over to the [Issues](https://github.com/nokau/Barotrauma.zht.edited.mod/issues) page and click on the green `New issue` button, then select an issue type.

### Share suggestions

Head over to the [Discussions](https://github.com/nokau/Barotrauma.zht.edited.mod/discussions) page and click on the green `New discussion` button, then select an discussion type.

Since this is a Traditional Chinese localization, please send your issues/discussions in Traditional Chinese if possible.

# For now this project has most of the texts edited, including:
- Main menu UI
- Gameplay UI
- Editor UIs
- Names and descriptions of devices, items
- Events and missions
- NPC conversations

### Notes
- Multiplayer texts like error messages, server managments, etc., might be way less complete/correct than other parts of the game.
- Name differences for some items and devices.
-	~~The item parameters in Submarine Editor, as well as the components(Wifi, Sin, Cos, etc.) are still in English.~~
    - Since game version v0.21.6.0, Editor UI and item parameters are now mostly translated.
- Component names (Wifi, Sin, Cos, etc.) are un-translated.
- Most of the character and location names within missions and events are un-translated since all the generated names have no translation either.
- These ship names are un-translated: Bunyip, Muikku, Selkie, Kastrull, Herja.

# Files
Inside the [current_version](./current_version) folder, there are 10 files in total:

### NPC conversations:
Vanilla file at `...\Barotrauma\Content\NPCConversations\TraditionalChinese`
- **NpcConversations_TraditionalChinese.xml**

### UI/Game texts:
Vanilla files at `...\Barotrauma\Content\Texts\TraditionalChinese`
- **TraditionalChineseVanilla.xml** - Gameplay UI, items, events, etc.
  - This file is a combination of ~Vanilla.xml and ~VanillaNew.xml
- **TraditionalChineseVanillaEditorTexts.xml** - Editor related items, UI, etc.
- **TraditionalChineseVanillaEndgame.xml** - Story related texts
- **TraditionalChineseVanillaFactions.xml** - Faction related texts

### Other files:
- filelist.xml - Mod content package list
- PreviewImage.png - Mod thumbnail
- LICENSE.txt
- readme_EN.txt
- readme_TC.txt

# Recommended Tools
- Notepad++
