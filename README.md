# 浏览器助手

Windows 桌面浏览器扩展管理与网页辅助工具。支持本地 ZIP / 7Z 插件升级、Google Drive 云端升级检查、备份恢复、网页关键词高亮、Messenger 白名单呼叫及网页静音。

## 下载

请前往 [Releases](https://github.com/beckli0707-blip/browser-assistant/releases/latest) 下载软件。

- 单文件 EXE：适合直接分发和启动。
- BrowserAssistant-win-x64.zip：完整目录包，也是软件自动更新使用的资源；解压全部文件后启动，不要单独移动目录版 EXE。
- BrowserAssistant-Plugin.zip：浏览器扩展，解压后在扩展管理页开启开发者模式，选择“加载已解压的扩展程序”。
- SHA256SUMS.txt：下载文件的 SHA-256 校验清单。

## 使用

1. 使用 64 位 Windows，并确保已安装 Microsoft Edge WebView2 Runtime。7Z 升级还需要 64 位 7-Zip，建议保持更新。
2. 启动软件，在设置中下载并安装浏览器扩展。
3. 复制扩展 ID，回到软件“设置 → 插件连接”完成登记；不同浏览器 Profile 分别登记。
4. 软件更新仓库填写 `beckli0707-blip/browser-assistant`。
5. MSG 呼叫需要桌面名单授权；呼叫数表示点击按钮数，不保证响铃或接听。

## 安全与范围

当前程序尚未进行可信发布者代码签名，Windows 可能提示或阻止运行。请核对来源与校验值，不建议关闭系统防护。升级包的哈希校验用于完整性检查，不等于发布者签名。

## 源码说明

本仓库仅公开软件发布包和使用说明，不公开完整应用源码。GitHub 自动生成的 Source code (zip/tar.gz) 仅包含仓库文档，不是完整应用源码，也不是可运行的软件包。
