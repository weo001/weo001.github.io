# 開發者網站（weo001.github.io）

所有遊戲共用的網站根目錄，公開儲存庫 `weo001/weo001.github.io`，網址 https://weo001.github.io/ 。

- `app-ads.txt`：AdMob 驗證用（發布商 pub-4447189266414871），一定要放在網域最上層。每款有廣告的遊戲在 App Store Connect 的「行銷網址」都填 https://weo001.github.io/ 。
- `index.html`：遊戲列表，連到各遊戲的支援網站。新遊戲上架就加一張卡片。

改完在這個資料夾 git add -A、commit、push，約 1 分鐘生效。
- `studio.json`：遊戲裡「邀請好友」連的伺服器網址（`invite`）。空的就代表還沒開放。換伺服器只要改這個檔，不用重新上架。說明看 `Desktop\claude\行銷推廣\`。
