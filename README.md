# 微软商店 MSIX 管理器 / Microsoft Store MSIX Manager

## 中文

微软商店 MSIX 管理器是一款面向 Windows 用户的免费工具，适用于 Windows Server、精简版 Windows 或无法直接使用 Microsoft Store 的环境。它可以通过 Microsoft Store 应用 ID 或应用链接查询、下载并安装免费公开应用的 MSIX/AppX 安装包。

### 主要功能

- 输入 Microsoft Store 应用 ID 或完整应用链接。
- 选择目标架构：x64、x86、arm64、arm。
- 指定安装包下载目录。
- 对比已安装版本、云端最新版本和本地已下载版本。
- 下载免费公开应用的 MSIX/AppX 安装包。
- 安装或更新目标应用。
- 在本地历史安装包列表中右键安装任意历史版本。
- 自动识别并处理常见依赖包。
- 安装前尝试停止目标应用残留进程。
- 安装失败时显示诊断信息。
- 支持简体中文和英文界面。
- 在关于页面检查本工具更新、查看更新日志、下载并安装新版本。

### 下载

请前往 [Releases 页面](https://github.com/zuelu/msstore-msix-manager/releases/latest) 下载：

`MSStoreMsixManager.exe`

下载后双击运行即可。

### 基本使用

1. 打开 `MSStoreMsixManager.exe`。
2. 在应用 ID 输入框中填写 Microsoft Store 应用 ID，或粘贴完整应用链接。
3. 选择需要下载的架构。
4. 选择安装包保存目录。
5. 点击“查询版本”，查看已安装版本、云端最新版本和本地已下载版本。
6. 需要下载时，点击“下载最新包”。
7. 需要安装或更新应用时，点击“安装/更新”。
8. 如需安装历史版本，可在本地已下载安装包列表中右键选择安装。
9. 如需检查本工具更新，可进入“关于”页面点击“检查更新”。

详细步骤请查看 [安装使用说明](./INSTALL.md)。

### 如何获取应用 ID

1. 打开 [Microsoft Store 网页版](https://apps.microsoft.com/)。
2. 搜索需要下载的应用。
3. 进入应用详情页。
4. 复制链接中的应用 ID。

示例：

```text
https://apps.microsoft.com/detail/9plm9xgg6vks
```

其中 `9plm9xgg6vks` 就是应用 ID。

### 注意事项

- 本工具主要用于 Microsoft Store 中的免费公开应用。
- 付费应用、私有应用、区域受限应用或需要特殊许可证的应用，可能无法下载或安装。
- MSIX/AppX 应用的实际安装位置由 Windows 系统管理。
- 安装或更新应用时，建议使用管理员权限运行本工具。
- 如果系统策略限制 AppX/MSIX 安装，需要先调整系统策略后再使用。

### 更新日志

请查看 [CHANGELOG.md](./CHANGELOG.md)。

## English

Microsoft Store MSIX Manager is a free Windows utility for Windows Server, lightweight Windows builds, and other environments where Microsoft Store is not directly available. It helps users query, download, and install MSIX/AppX packages for free public Microsoft Store apps by using a Store app ID or app link.

### Main Features

- Enter a Microsoft Store app ID or full app link.
- Choose the target architecture: x64, x86, arm64, or arm.
- Select a download folder for installation packages.
- Compare the installed version, latest cloud version, and latest local downloaded version.
- Download MSIX/AppX packages for free public Store apps.
- Install or update target apps.
- Right-click local package history to install any previously downloaded version.
- Detect and handle common dependency packages automatically.
- Try to stop residual app processes before installation.
- Show diagnostic information when installation fails.
- Switch between Simplified Chinese and English.
- Check updates for this tool from the About page, view release notes, download updates, and install the new version.

### Download

Download from the [Releases page](https://github.com/zuelu/msstore-msix-manager/releases/latest):

`MSStoreMsixManager.exe`

After downloading, double-click the file to run it.

### Basic Usage

1. Open `MSStoreMsixManager.exe`.
2. Enter a Microsoft Store app ID or paste a full app link.
3. Choose the target architecture.
4. Choose a folder to save downloaded packages.
5. Click Check versions to view the installed version, latest cloud version, and latest local downloaded version.
6. Click Download latest package when you need to download the package.
7. Click Install/Update when you need to install or update the app.
8. To install an older version, right-click a package in the local downloaded package list and choose install.
9. To check updates for this tool, open the About page and click Check for updates.

For detailed steps, see [Installation and Usage Guide](./INSTALL.md).

### How To Get An App ID

1. Open the [Microsoft Store web page](https://apps.microsoft.com/).
2. Search for the app you want to download.
3. Open the app details page.
4. Copy the app ID from the URL.

Example:

```text
https://apps.microsoft.com/detail/9plm9xgg6vks
```

In this example, `9plm9xgg6vks` is the app ID.

### Notes

- This tool is mainly for free public apps in Microsoft Store.
- Paid apps, private apps, region-restricted apps, or apps that require special licenses may not be downloadable or installable.
- The actual installation location of MSIX/AppX apps is managed by Windows.
- Administrator permission is recommended when installing or updating apps.
- If system policy blocks AppX/MSIX installation, adjust the system policy before using this tool.

### Changelog

See [CHANGELOG.md](./CHANGELOG.md).

## 作者信息 / Author

作者：云遮天  
Telegram：[@czzzru](https://t.me/czzzru)  
QQ：80795151  
网站：[https://czzz.ru](https://czzz.ru)
