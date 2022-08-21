# Barotrauma-zht-edited
[Barotrauma](https://store.steampowered.com/app/602960/Barotrauma/)

[English README](./README_eng.md)

[這個Mod的Steam工作坊頁面](https://steamcommunity.com/sharedfiles/filedetails/?id=2804180128)

# 這是什麼?
這是一個基於官方繁體中文、參考官方英文進行調整的繁體中文文本Mod。文本檔案內容盡量以當前版本的官方英文文本檔案內容進行排序，以便對照。

僅以個人經驗與偏好進行調整，還請斟酌使用；我無法保證這個文本中語句和詞彙的精確度等等，但歡迎在使用時自行對它進行編輯，編輯後也勿忘備份以免Steam進行遊戲更新或驗證遊戲檔案時被原始版本覆蓋。

- ### 我有問題想要回報
可以至 [Issues](https://github.com/nokau/Barotrauma.zht.edited.mod/issues) 頁面，點選右方綠色的 `New issue` 按鈕，進入新頁面之後點選位於對應主題其中一項右方的綠色 `Get started` 按鈕。

- ### 我想直接貢獻心力
我對GitHub這方面的功能並不熟悉，所以如果想要在此對專案內容進行修改的話，還請建立額外版本並請避免直接修改原始檔案。

# 這個Mod目前調整了下列遊戲元素的文本
- 主選單UI
- 遊戲中UI
- 部分潛艇編輯器UI
- 遊戲中可互動設備、物品名稱與描述
- 任務與事件
- NPC對話

### 備註
- 部分物件名稱與官方繁體中文文本有極大差異。
- 潛艇編輯器中物件的細部設定、功能元件 (Wifi、Sin、Cos...等等) 的細部設定尚為英文。
- 配合大部分隨機生成的NPC和地區名稱都尚無翻譯，保留了任務與事件中提到的人物與地區等的英文名稱。
- 保留 Bunyip、Muikku、Selkie、Kastrull、Herja 船艦名稱。

# 專案中的檔案
在此專案中的 [current_version](./current_version) 資料夾裡:

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

# 額外檔案
在此專案中的 [current_version_extra](./current_version_extra) 資料夾裡:

### TCVanillaEditorTexts.SP.xml
 - 修改自上述3個檔案中的 TCVanillaEditorTexts.xml，這個檔案包含了潛艇編輯器與遊戲中物件細部設定的翻譯但尚不完整。

# 推薦工具
- Notepad++
