# 微软商店 MSIX 管理器 / Microsoft Store MSIX Manager

## 中文

微软商店 MSIX 管理器是一款面向 Windows 用户的免费工具，适用于 Windows Server、精简版 Windows、无法打开 Microsoft Store，或需要手动保存 MSIX/AppX 安装包的环境。

你可以输入 Microsoft Store 应用 ID 或应用详情页链接，查询、下载并安装免费公开应用的 MSIX/AppX 安装包，也可以保留本地历史版本并按需回退安装。

### 主要功能

- 输入 Microsoft Store 应用 ID 或完整应用链接。
- 选择下载架构：x64、x86、arm64、arm。
- 自定义安装包下载目录。
- 对比已安装版本、云端最新版本和本地已下载版本。
- 下载免费公开应用的 MSIX/AppX 安装包。
- 自动处理常见依赖包。
- 安装或更新前尝试停止目标应用残留进程。
- 在本地历史安装包列表中右键安装任意历史版本。
- 支持简体中文和英文界面切换。
- 在“关于”页面检查本软件更新、查看更新说明、下载并手动安装新版。
- 下载失败时自动重试，并在必要时切换备用下载方式，提高大文件下载稳定性。

### 下载

请前往 [Releases 页面](https://github.com/zuelu/msstore-msix-manager/releases/latest) 下载：

```text
MSStoreMsixManager.exe
```

下载后双击运行即可。安装或更新应用时，建议右键选择“以管理员身份运行”。

### 基本使用

1. 打开 `MSStoreMsixManager.exe`。
2. 输入 Microsoft Store 应用 ID，或粘贴完整应用详情页链接。
3. 选择需要下载的架构。
4. 选择安装包保存目录。
5. 点击查询，查看已安装版本、云端最新版本和本地已下载版本。
6. 需要下载时，点击下载按钮。
7. 需要安装或更新应用时，点击“安装/更新”。
8. 如需安装历史版本，在本地已下载安装包列表中右键选择安装。

更详细的步骤请查看 [安装使用说明](./INSTALL.md)。

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
- 如果系统策略限制 AppX/MSIX 安装，需要先调整系统策略后再使用。
- 下载速度会受到 Microsoft 下载节点、网络线路、系统代理、杀毒软件和磁盘写入速度影响。

### 更新日志

请查看 [CHANGELOG.md](./CHANGELOG.md)。

## English

Microsoft Store MSIX Manager is a free Windows utility for Windows Server, lightweight Windows builds, systems without direct Microsoft Store access, and users who need to manually save MSIX/AppX installers.

You can enter a Microsoft Store app ID or app detail link to query, download, and install MSIX/AppX packages for free public Store apps. You can also keep local historical packages and install an older version when needed.

### Main Features

- Enter a Microsoft Store app ID or full app link.
- Choose the target architecture: x64, x86, arm64, or arm.
- Choose a custom package download folder.
- Compare the installed version, latest cloud version, and latest local downloaded version.
- Download MSIX/AppX packages for free public Store apps.
- Handle common dependency packages automatically.
- Try to stop residual target app processes before installing or updating.
- Right-click local package history to install any previously downloaded version.
- Switch between Simplified Chinese and English.
- Check software updates from the About page, view release notes, download updates, and install them manually.
- Retry failed downloads automatically and use a fallback download method when needed for better large-file stability.

### Download

Download from the [Releases page](https://github.com/zuelu/msstore-msix-manager/releases/latest):

```text
MSStoreMsixManager.exe
```

After downloading, double-click the file to run it. Running as administrator is recommended when installing or updating apps.

### Basic Usage

1. Open `MSStoreMsixManager.exe`.
2. Enter a Microsoft Store app ID or paste a full app detail link.
3. Choose the target architecture.
4. Choose a folder to save downloaded packages.
5. Click Check versions to view the installed version, latest cloud version, and latest local downloaded version.
6. Click Download when you need to download the package.
7. Click Install/Update when you need to install or update the app.
8. To install an older version, right-click a package in the local downloaded package list and choose install.

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
- If system policy blocks AppX/MSIX installation, adjust the system policy before using this tool.
- Download speed may be affected by Microsoft download nodes, network routes, system proxy settings, antivirus software, and disk write speed.

### Changelog

See [CHANGELOG.md](./CHANGELOG.md).

## 作者信息 / Author

作者：云遮天  
Telegram：[@czzzru](https://t.me/czzzru)  
QQ：80795151  
网站：[https://czzz.ru](https://czzz.ru)
