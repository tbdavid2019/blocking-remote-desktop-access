# 自訂AdGuard Home遠端桌面訪問過濾規則

## 簡介
本規則集旨在阻止非法或未經授權的遠端桌面訪問工具，如TeamViewer、AnyDesk等。此外，還附上了台灣IP清單（taiwan-ip-list），以便於精確的網路管理。

## 過濾規則
- **規則1**: 阻止TeamViewer連線
- **規則2**: 阻止AnyDesk連線
- **規則3**: 阻止其他常見遠端訪問工具連線（詳見[toollist.md](./toollist.md)）

- 世界 ip 列表 https://github.com/herrbischoff/country-ip-blocks/tree/master
  

## 使用方法
1. 登入AdGuard Home管理面板
2. 前往「過濾器」頁面
3. 點擊「添加過濾器」
4. 將本倉庫中的`blocking-remote-desktop-rules.txt`內容複製貼上到自訂過濾規則
5. 儲存變更，規則將立即生效

## 規則說明
- 這些規則僅針對阻止非法或未經授權的連線，不影響正常的管理需求。
- 可選：排除本地網路或管理IP段的連線，以確保合法的管理訪問不受影響。

## 貢獻
歡迎提交Issue或Pull Request，以幫助優化和完善規則集。如果有任何問題或建議，請隨時與我們聯繫。

---

# Custom AdGuard Home Rules to Block Remote Desktop Access

## Introduction
This ruleset aims to block unauthorized remote desktop access tools such as TeamViewer, AnyDesk, etc. It also includes a Taiwan IP list for precise network management.

## Filtering Rules
- **Rule 1**: Block TeamViewer connections
- **Rule 2**: Block AnyDesk connections
- **Rule 3**: Block other common remote access tools (see [toollist.md](./toollist.md) for details)

## Usage
1. Log in to the AdGuard Home admin dashboard
2. Go to the "Filters" page
3. Click "Add Filter"
4. Copy and paste the contents from `blocking-remote-desktop-rules.txt` in this repository
5. Save changes to activate the rules

## Rule Details
- These rules are designed to block unauthorized access without affecting legitimate admin requirements.
- Optional: Exclude LAN/admin IP ranges to ensure authorized management access remains unaffected.

## Contributing
Feel free to submit issues or pull requests to help optimize and enhance the ruleset. If you have any questions or suggestions, please don't hesitate to reach out.
