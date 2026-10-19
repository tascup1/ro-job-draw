# 樂園轉職籤

RO 仙境傳說 Online：樂園的轉職抽籤小網站。按「抽籤」從目前已開放的職業裡隨機抽一個，不滿意可以「重抽」（不會抽到跟上一次一樣的）。

**Demo：https://tascup1.github.io/ro-job-draw/**

## 籤筒裡的職業

依 [樂園官網公告](https://roz.gnjoy.com.tw/Notice/Notice_List) 整理（2026/10）：

- **二轉（13）**：騎士、十字軍、巫師、賢者、刺客、流氓、祭司、武道家、鐵匠、鍊金術師、獵人、詩人、舞孃
  - 來源：[【職業】二次轉職](https://roz.gnjoy.com.tw/Notice/Notice_Info?id=217706)、[【職業】職業公會大突破-進階技能習得](https://roz.gnjoy.com.tw/Notice/Notice_Info?id=218070)
- **擴充職業（2）**：忍者（2026/05/19 開放）、神槍手（2026/09/22 開放）

之後官方開放新職業時，改 `index.html` 裡的 `JOBS` 陣列即可。

## 檔案

| 檔案 | 內容 |
|---|---|
| `index.html` | 整個網站（HTML + CSS + JS，沒有建置步驟） |
| `cat.jpg` | 背景與頭像的貓咪照片 |

本機預覽：直接用瀏覽器打開 `index.html`。

## 部署

使用 GitHub Pages（Settings → Pages → Deploy from a branch → `main` / root），push 到 `main` 後約 1 分鐘自動更新。
