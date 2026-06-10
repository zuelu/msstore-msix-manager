# 更新日志 / Changelog

## v1.1.1

### 中文

本版本优化下载体验和中文日志显示，适合所有正在使用中文界面或需要下载较大 MSIX/AppX 安装包的用户更新。

更新内容：

- 优化“下载最新包”的下载方式，优先使用系统自带下载能力处理大文件。
- 改进下载失败后的重试和回退处理。
- 修复中文模式下日志输出乱码的问题。
- 修复日志中可能出现 PowerShell 序列化内容的问题。
- 改进中文路径和中文参数下的启动兼容性。
- 更新中英文 README 和安装使用说明。

### English

This release improves package download behavior and Chinese log output. It is recommended for users who use the Chinese interface or download large MSIX/AppX packages.

Changes:

- Improved Download latest package behavior by preferring the system download capability for large files.
- Improved retry and fallback handling after download failures.
- Fixed garbled Chinese log output in Chinese mode.
- Fixed possible PowerShell serialized output in logs.
- Improved startup compatibility for Chinese paths and Chinese parameters.
- Updated bilingual README and installation guide.

## v1.1.0

### 中文

本版本新增多语言界面和软件更新功能，提升日常使用与后续升级体验。

更新内容：

- 新增简体中文和英文界面切换。
- 管理界面、关于页面、日志信息和软件自身错误信息会跟随所选语言显示。
- 关于页面新增“检查更新”功能。
- 支持查看当前版本与 GitHub 最新版本对比。
- 支持查看版本更新日志。
- 支持下载新版本安装包。
- 支持手动点击安装更新。
- 优化命令行输出的中文显示。

### English

This release adds multilingual UI support and software update features, improving daily usage and future upgrades.

Changes:

- Added Simplified Chinese and English UI switching.
- The management page, About page, log messages, and app-owned error messages follow the selected language.
- Added Check for updates to the About page.
- Added current version and latest GitHub version comparison.
- Added release notes display.
- Added update download support.
- Added manual install update action.
- Improved Chinese output in the command-line wrapper.

## v1.0.0

### 中文

首次发布“微软商店 MSIX 管理器”。

主要功能：

- 支持输入 Microsoft Store 应用 ID 或应用链接。
- 支持选择 x64、x86、arm64、arm 架构。
- 支持查询已安装版本、云端最新版本和本地已下载版本。
- 支持下载免费公开应用的 MSIX/AppX 安装包。
- 支持安装、更新和右键安装历史版本。
- 自动处理常见依赖包。
- 安装前尝试停止目标应用残留进程。
- 安装失败时显示诊断信息，便于排查。

### English

Initial release of Microsoft Store MSIX Manager.

Main features:

- Enter a Microsoft Store app ID or app link.
- Choose x64, x86, arm64, or arm architecture.
- Check installed version, latest cloud version, and latest local downloaded version.
- Download MSIX/AppX packages for free public Store apps.
- Install, update, and right-click to install historical local packages.
- Handle common dependency packages automatically.
- Try to stop residual target app processes before installation.
- Show diagnostic information when installation fails.
