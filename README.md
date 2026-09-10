# 餐飲零售內容匯流 Skill

將餐飲零售的商家資料或長文，轉為部落格文章、Facebook、Instagram、Threads、LINE 文案、圖像及短影音腳本；依你的請求，透過可用工具發布、儲存草稿或排程。預設使用繁體中文。

## 安裝

[開啟 Skill 資料夾](https://github.com/seedream0311-ai/restaurant-retail-content-flow/tree/main/skills/restaurant-retail-content-flow)

在自己的 Codex 貼上以下文字，交由技能安裝工具處理：

```text
使用 $skill-installer，從以下 GitHub 資料夾安裝餐飲零售內容匯流 Skill：
https://github.com/seedream0311-ai/restaurant-retail-content-flow/tree/main/skills/restaurant-retail-content-flow
```

安裝後於下一次對話輸入 `$restaurant-retail-content-flow` 使用。若尚未載入，重新開啟對話或重啟 Codex；已有同名 Skill 時，先確認版本與更新方式。

### 手動下載安裝

1. 在 GitHub 儲存庫首頁選擇 **Code → Download ZIP**，下載並解壓縮。
2. 找到解壓縮後的 `skills/restaurant-retail-content-flow` 資料夾，完整複製這個資料夾；不要把整個儲存庫當成一個 Skill。
3. 放進 Codex 的個人技能目錄。依目前官方目錄慣例為 `~/.agents/skills/`（`~` 是使用者家目錄）；部分既有環境或安裝工具仍使用 `~/.codex/skills/`，請以自己的 Codex 版本實際載入位置為準。

安裝後結構應為：

```text
~/.agents/skills/restaurant-retail-content-flow/
├── SKILL.md
├── agents/openai.yaml
└── references/publishing.md
```

## 先試產生內容

```text
使用 $restaurant-retail-content-flow。
以下是虛構教學案例：一家文具選物店販售筆記本與收納用品，
對象是想整理工作桌的上班族，主要行動是邀請讀者分享整理困擾。
請生成部落格文章、四平台文案、教學示意圖與短影音拍攝腳本。
沒有提供的價格、優惠、地址或商品效果，請勿補造。
這次只產生內容，不發布、不建立遠端草稿。
```

## 發布到指定帳號

先換成自己的真實帳號名稱，再貼上使用；發布內容須使用已確認的真實資料，不直接沿用上面的虛構教學案例。

```text
使用 $restaurant-retail-content-flow。
沿用本次已確認的文章、文案與配圖，立即發布到：
Facebook 粉專「填入我的粉專名稱」、Instagram「填入我的帳號」。
LINE 官方帳號「填入我的官方帳號名稱」只私訊給「填入收件人名稱」，不群發。
操作前核對帳號與收件人；其他平台不發布。
如缺少登入或權限，告訴我受影響的平台。完成後提供實際結果與可取得的貼文連結。
```

## 使用條件

- 產生實際圖片需要可用的圖片工具；網站或社群操作需要相應連接器、API 或瀏覽器工具。
- 每位學員自行配置工具並登入有權管理的帳號。安裝 Skill 不會一併安裝工具、取得發布權限或搬移他人的登入狀態。
- LINE 須指定 VOOM 貼文、私訊或群發，以及相應帳號與收件範圍；短影音腳本不等於成片，影片發布需另備完成的影片。

技能版本為 0.2。本套件包含上述三個技能檔案，不含私人帳號設定、文章、圖片或發布紀錄；不同裝置仍須確認工具與登入是否可用。
