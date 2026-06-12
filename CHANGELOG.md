# 更新日志 / Changelog

## v1.1.3

### 中文

本版本修复安装或更新应用时的依赖包识别问题，建议已经下载过多个历史版本安装包的用户更新。

更新内容：

- 修复本地目录中存在同一应用历史安装包时，旧版主包可能被误当作依赖包传给 Windows 安装流程的问题。
- 解决因此导致的安装失败提示：同一个程序包被指定多次。
- 错误信息过长时，弹窗会保留最后的关键错误行，方便查看真实安装错误。
- 保留历史安装包和右键安装历史版本功能。

### English

This release fixes dependency detection during app installation or update. Updating is recommended for users who keep multiple historical package versions in the same local folder.

Changes:

- Fixed an issue where an older main package of the same app could be treated as a dependency when historical packages exist in the local folder.
- Resolved installation failures caused by passing the same package identity more than once to Windows deployment.
- Long error dialogs now keep the final key error lines so the real installation error remains visible.
- Historical packages and right-click installation of older versions remain supported.

## v1.1.2

### 中文

本版本继续优化“下载最新包”的稳定性，适合经常下载较大 MSIX/AppX 安装包的用户更新。

更新内容：

- 修复部分网络环境下下载连接被重置后，备用下载方式没有继续执行的问题。
- 下载失败时会更稳定地进入重试和备用下载流程。
- 下载中断后会清理未完成的临时文件，减少下次下载受到残留文件影响的情况。
- 保留中文模式下的日志输出优化，继续减少乱码和无关 PowerShell 输出。

### English

This release further improves Download latest package stability, especially for users who often download large MSIX/AppX packages.

Changes:

- Fixed an issue where the fallback download method might not continue after a reset connection in some network environments.
- Improved retry and fallback behavior after download failures.
- Incomplete temporary files are cleaned after interrupted downloads to reduce impact on the next attempt.
- Keeps the Chinese log output improvements to reduce garbled text and unrelated PowerShell output.

## v1.1.1

### 中文

本版本优化下载体验和中文日志显示，建议使用中文界面或经常下载较大 MSIX/AppX 安装包的用户更新。

更新内容：

- 优化“下载最新包”的下载方式，提升大文件下载稳定性。
- 改进下载失败后的重试和回退处理。
- 修复中文模式下日志输出乱码的问题。
- 修复日志中可能出现 PowerShell 序列化内容的问题。
- 改进中文路径和中文参数下的启动兼容性。
- 更新中英文 README 和安装使用说明。

### English

This release improves package download behavior and Chinese log output. Updating is recommended for users who use the Chinese interface or often download large MSIX/AppX packages.

Changes:

- Improved Download latest package behavior for better large-file download stability.
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
- 管理界面、关于页面、日志信息和软件自有错误信息会跟随所选语言显示。
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
