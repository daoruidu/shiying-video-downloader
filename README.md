<p align="center"><img src="assets/shiying-logo.svg" alt="拾影 Shiying Logo" width="760"></p>

# 🎬 拾影 | Shiying Video Downloader

**Windows 视频下载管理器 · C# / WPF / .NET**

拾影是一款面向 Windows 的桌面视频下载工具，支持抖音和快手视频链接，用于保存用户本人拥有或已获得授权的视频。当前提供 **v0.1.1 便携预览版**，暂不提供去水印功能。

Shiying is a Windows desktop video download manager for videos users own or are authorized to save. It supports Douyin and Kuaishou links. The current build is a portable preview; watermark removal is not provided.

**平台 / Platform:** Windows 10/11 x64 · **版本 / Version:** v0.1.1 Preview · **源码 / Source:** Not publicly released

## 📥 下载 | Download

### [⬇️ 下载拾影 v0.1.1 Windows 便携版 / Download ZIP](https://github.com/daoruidu/shiying-video-downloader/releases/download/v0.1.1/Shiying-v0.1.1-portable-win-x64.zip)

[查看版本说明与附件 / Release details](https://github.com/daoruidu/shiying-video-downloader/releases/tag/v0.1.1)

**压缩包：** `Shiying-v0.1.1-portable-win-x64.zip`（约 370 MB）

### 使用方法 | Quick Start

1. 下载 ZIP，**完整解压**到本地文件夹，不要直接在压缩包内运行。
2. 在解压目录中运行 `VideoDownloadManager.exe`。
3. 保留 `WebView2Runtime` 等随包文件，不要单独移动 EXE。
4. 粘贴本人拥有或已获授权的视频分享链接，选择保存目录后下载。

The package includes the required .NET runtime and a fixed WebView2 runtime, so a separate installation is normally unnecessary.

📖 [使用前请看](docs/使用前请看.txt) · [详细使用说明](docs/使用说明.txt)

## 📸 软件截图 | Screenshots

![拾影 Windows 桌面软件主界面](assets/screenshots/main-window.png)

## ✨ 主要功能 | Features

- ✅ 抖音、快手双平台链接支持 / Douyin & Kuaishou links
- ✅ Windows 原生 WPF 界面 / Native WPF desktop UI
- ✅ 下载任务队列、取消和失败重试 / Task queue, cancel & retry
- ✅ SQLite 本地下载历史 / Local SQLite history
- ✅ 内置 WebView2 网页解析 / Embedded WebView2-based parsing
- ✅ 可选 yt-dlp 下载引擎 / Optional yt-dlp engine
- ✅ 自包含 Windows x64 便携包 / Self-contained portable build

> 本版是开发预览版。平台页面、访问权限或网络变化可能影响部分链接的解析与下载。  
> This is a preview release; platform changes, permissions and network conditions may affect downloads.

## 🛠️ 技术栈 | Technology

| 技术 / Technology | 用途 / Purpose |
|---|---|
| C# / .NET | 桌面应用与业务逻辑 / Application logic |
| WPF | Windows 桌面界面 / Desktop UI |
| SQLite | 下载任务与历史 / Local history |
| WebView2 | 内置网页解析 / Embedded web parsing |
| yt-dlp（可选） | 可选解析与下载引擎 / Optional download engine |

## 🗺️ 开发计划 | Roadmap

- [x] WPF 桌面界面
- [x] 抖音、快手支持
- [x] 下载队列、取消与重试
- [x] SQLite 本地历史记录
- [x] v0.1.1 Windows x64 便携预览版
- [ ] 完善兼容性、错误提示与用户体验
- [ ] 改进安装、更新和分发体验
- [ ] 评估正式版授权与收费方案

## ⚠️ 使用与版权说明 | Usage & Copyright

请仅保存本人拥有或已获得合法授权的视频，并遵守适用法律法规、版权要求和相关平台服务条款。使用者须自行确认其下载行为及获取方式获得许可。

Download only videos you own or are authorized to save, and comply with applicable laws, copyright requirements and platform terms.

本公开仓库用于**产品展示、下载与用户文档**，不提供完整的 C# 源码。GitHub 自动生成的 “Source code” 压缩包仅包含本公开仓库文件。

This public repository contains product information and user documentation, not the private C# application source.

## 💬 反馈 | Feedback

遇到问题可以通过 [GitHub Issues](https://github.com/daoruidu/shiying-video-downloader/issues) 反馈，建议提供 Windows 版本、软件版本、报错描述（请隐去个人信息和私密链接）。

Developed by [Daorui Du](https://github.com/daoruidu)

⭐ 如果这个项目对你有帮助，欢迎 Star。
