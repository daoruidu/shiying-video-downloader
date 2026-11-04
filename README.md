# 🎬 拾影 | Shiying Video Downloader

### Windows 视频下载管理器 | Windows Video Download Manager

拾影是一款基于 **C# / WPF / .NET** 开发的 Windows 桌面视频下载工具，面向需要保存本人拥有或已获授权视频的用户。

Shiying is a Windows desktop video download manager built with C#, WPF, and .NET, designed for downloading videos that users own or are authorized to save.

> 🚧 当前版本：v0.1.1 Preview  
> 支持系统：Windows 10 / 11 x64  
> 当前状态：开发预览版，功能持续完善中。

## ✨ 核心功能 | Features

- 🎬 支持抖音和快手视频链接
- 🖥️ 原生 Windows WPF 桌面界面
- 📥 视频下载任务队列
- 🔄 下载取消与失败重试
- 🗄️ SQLite 本地历史记录
- 🌐 WebView2 内置网页解析
- ⚙️ 可选 yt-dlp 下载引擎
- 📦 .NET 和 WebView2 固定运行时随便携包提供
- 🔒 不提供去水印功能

## 🛠️ 技术架构 | Technology Stack

| 技术 | 用途 |
|---|---|
| C# / .NET | 核心开发语言与运行平台 |
| WPF | Windows 桌面界面 |
| SQLite | 本地任务和历史记录 |
| WebView2 | 内置网页解析 |
| yt-dlp | 可选视频解析与下载工具 |

## 📸 软件截图 | Screenshots

### 🖥️ 软件主界面 | Main Window

![拾影主界面](assets/screenshots/main-window.png)


## 📦 下载与安装 | Installation

当前提供 Windows x64 便携预览版。

1. 获取 `拾影-0.1.1-portable-win-x64.zip`。
2. 将压缩包完整解压至本地文件夹。
3. 运行 `VideoDownloadManager.exe`。
4. 保留原有目录结构及 `WebView2Runtime` 文件夹。

该便携版已包含所需的 .NET 与 WebView2 固定运行时，正常情况下不需要另外安装。

## ⚠️ 使用声明 | Disclaimer

本软件仅用于下载用户本人拥有或已获得合法授权的视频内容。

请遵守适用法律法规、内容版权要求及相关平台服务条款。

This application is intended only for downloading videos that users own or have permission to save. Users are responsible for complying with applicable laws, copyright requirements, and platform terms.

## 🗺️ 后续计划 | Roadmap

- [x] WPF 桌面界面
- [x] 抖音、快手双平台支持
- [x] 下载任务队列
- [x] SQLite 历史记录
- [x] 取消与重试
- [x] Windows x64 便携预览版
- [ ] 完善错误提示和用户体验
- [ ] 完善安装、更新及分发方式
- [ ] 评估正式版本的授权与收费方案

## 👨‍💻 Author

Developed by [Daorui Du](https://github.com/daoruidu)

---

⭐ 如果这个项目对你有帮助，欢迎 Star 关注项目进展。

*Build useful software. Keep improving.*
