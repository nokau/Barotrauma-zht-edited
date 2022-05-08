# Barotrauma-zht-edited
[ENG README](./README_eng.md)

[Steam工作坊](https://steamcommunity.com/sharedfiles/filedetails/?id=2804180128)

# 這是什麼?
這是一個基於官方繁體中文、參考官方英文進行調整的繁體中文文本Mod。文本檔案內容盡量以當前版本的官方英文文本檔案內容進行排序，以便對照。

還請斟酌使用，我無法保證這個文本中用語與詞彙的精確度等等，但歡迎在使用時自行對它進行編輯，編輯後也勿忘備份。

### 我有問題想要回報
可以至 [Issues](https://github.com/nokau/Barotrauma.zht.edited.mod/issues) 頁面，點選右方綠色的 `New issue` 按鈕，進入新頁面之後點選位於2個對應主題其中一項右方的綠色 `Get started` 按鈕。

### 我想直接貢獻心力
我對GitHub這方面的功能並不熟悉，所以如果想要在此對專案內容進行修改的話，還請建立額外版本並請避免直接修改原始檔案。

# 這個Mod的文本調整了下列遊戲元素
- 主選單UI
- 遊戲中UI
- 部分潛艇編輯器UI
- 遊戲中可互動設備、物品名稱與描述
- 任務與事件
- NPC對話

### 備註
- 部分物件名稱與官方繁體中文文本有極大差異。
- 潛艇編輯器中物件的細部設定、功能元件 (Wifi、Sin、Cos...等等) 的細部設定尚為英文。
- 配合大部分隨機生成的NPC、地區名稱也都尚無翻譯，我保留了任務與事件中提到的人物與地區等的英文名稱。
- 保留 Bunyip、Muikku、Selkie、Kastrull、Herja 船艦名稱。

# 專案中的檔案
你能在這個專案中的[current_version](./current_version)資料夾裡找到以下提到的所有檔案:

### NpcConversations_TraditionalChinese.xml
- 這個檔案包含了編輯過的NPC對話。
- 這個檔案在遊戲資料夾中的路徑為`Steam\steamapps\common\Barotrauma\Content\NPCConversations\TraditionalChinese`

### TraditionalChineseVanilla.xml
- 由於翻譯文本似乎無法被遊戲以同樣於英文文本的方式讀取，這個檔案中包含了編輯過的三個在遊戲的英文文本路徑中的檔案內容。
- 這個檔案在遊戲資料夾中的路徑為`Steam\steamapps\common\Barotrauma\Content\Texts\TraditionalChinese`
- 如果想要與英文文本檔案進行對照，資料夾中也付有被合併至 TraditionalChineseVanilla.xml 前的3個文本檔案:
  - **TCVanilla.xml**
  - **TCVanillaEditorTexts.xml**
  - **TCVanillaNew.xml**

# 推薦工具
- Notepad++
