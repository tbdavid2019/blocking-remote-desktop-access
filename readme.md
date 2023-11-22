自定义AdGuard Home远程桌面访问过滤规则

## 简介
本规则收集的目的是阻止非法远程桌面访问工具,如TeamViewer、AnyDesk等。

## 过滤规则
- 规则1:阻止TeamViewer连线
- 规则2:阻止AnyDesk连线
- 规则3:阻止其他常见远程访问工具连线(列出工具名称)

## 使用方法
- 登录AdGuard Home管理面板
- 前往「过滤器」页面
- 点击「添加过滤器」
- 将本repo的custom-rules.txt内容复制粘贴到自定义过滤规则
- 保存更改即可生效

## 规则说明
- 规则仅针对阻止非法或未经授权的连线,不影响正常管理需求。
- 排除本地网络或管理IP段的连线(可选)

## 贡献
欢迎提交issue或PR来优化完善规则......

---

Custom AdGuard Home Rules to Block Remote Desktop Access

## Introduction
This ruleset aims to block unauthorized remote desktop access tools like TeamViewer, AnyDesk etc.

## Filtering Rules
- Rule 1: Block TeamViewer connections
- Rule 2: Block AnyDesk connections
- Rule 3: Block other common remote access tools (list tools)

## Usage
- Login to AdGuard Home admin dashboard
- Go to the "Filters" page
- Click "Add Filter"
- Copy and paste the contents from custom-rules.txt in this repo
- Save changes for them to take effect

## Rule Details
The rules only block unauthorized access, excluding legitimate admin requirements.
Optionally exclude LAN/admin IP ranges

## Contributing
Feel free to submit issues or PRs to improve the rulesets...
