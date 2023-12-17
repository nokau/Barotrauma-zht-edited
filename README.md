# Barotrauma-zht-edited
[Barotrauma on Steam](https://store.steampowered.com/app/602960/Barotrauma/) | [English README](./README_eng.md) | [這個Mod的Steam工作坊頁面](https://steamcommunity.com/sharedfiles/filedetails/?id=2804180128)

# 這是什麼?
這是一個基於電腦遊戲 Barotrauma 的官方繁體中文文本、參考其官方英文文本內容後進行調整的繁體中文文本Mod。文本內容盡量以當前版本的官方英文文本檔案內容進行排序，以便對照。

僅以個人經驗與偏好進行調整，還請斟酌使用；我無法保證這個文本中語句和詞彙的精確度等等。

- ### 問題回報、編輯建議
請至 [Issues](https://github.com/nokau/Barotrauma.zht.edited.mod/issues) 頁面，並點選右方綠色的 `New issue` 按鈕進入另一頁面後，再點選位於對應回報主題右方的綠色 `Get started` 按鈕。

# 這個Mod目前已調整了大部分遊戲元素文本，包含:
- 主選單UI
- 遊戲中UI
- 編輯器UI
- 設備、物品名稱與描述
- 任務與事件
- NPC對話

### 備註
- 若要進行多人遊戲，遊戲似乎需要所有玩家/主持方的遊戲原始檔案/部分Mod的內容一致。
- 多人遊戲的相關內容，包括錯誤訊息、伺服器管理等，較不如其他部分齊全/正確。
- 部分物件名稱與原始文本有極大差異。
- ~~潛艇編輯器中物件的細部設定、功能元件 (Wifi、Sin、Cos...等等) 的細部設定尚為英文。~~
  - 自遊戲版本 v0.21.6.0 後潛艇編輯器中的物件、細部設定等已有翻譯。
- 保留功能元件英文名稱 (Wifi、Sin、Cos...等等)。
- 配合大部分隨機生成的NPC和地區名稱都尚無翻譯，保留了任務與事件中提到的人物與地區等的英文名稱。
- 保留 Bunyip、Muikku、Selkie、Kastrull、Herja 船艦名稱。

# 專案中的檔案
在此專案中的 [current_version](./current_version) 資料夾裡，共有 5 個檔案，分別為

### NPC對話:

遊戲資料夾中的路徑為`Steam\steamapps\common\Barotrauma\Content\NPCConversations\TraditionalChinese`
- **NpcConversations_TraditionalChinese.xml**

### UI、遊戲文字:

遊戲資料夾中的路徑為`Steam\steamapps\common\Barotrauma\Content\Texts\TraditionalChinese`
- **TraditionalChineseVanilla.xml** - 遊戲UI、物品、任務等文字
  - 此為 ~Vanilla.xml 與 ~VanillaNew.xml 內容合併後的檔案
- **TraditionalChineseVanillaEditorTexts.xml** - 編輯器相關內容、UI等文字
- **TraditionalChineseVanillaEndgame.xml** - 故事特殊段落文字
- **TraditionalChineseVanillaFactions.xml** - 陣營相關內容文字

在此專案的舊版本資料夾內，除NPC對話外，其餘 .xml 檔案為我進行編輯時使用的檔案，與遊戲檔案名稱與內容有所出入。

# 推薦工具
- Notepad++
