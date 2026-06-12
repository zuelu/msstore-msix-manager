# 安装使用说明 / Installation and Usage Guide

## 中文

### 1. 下载软件

打开 [Releases 页面](https://github.com/zuelu/msstore-msix-manager/releases/latest)，下载：

```text
MSStoreMsixManager.exe
```

下载完成后，可以将文件放到任意常用目录，例如：

```text
D:\Tools\MSStoreMsixManager\
```

### 2. 启动软件

双击 `MSStoreMsixManager.exe` 启动。

如果安装或更新应用时遇到权限问题，请右键选择“以管理员身份运行”。

### 3. 选择界面语言

主界面支持简体中文和英文。打开软件后，可在语言下拉框中切换。切换后，管理界面、关于页面、日志信息和软件自身错误提示会同步切换到所选语言。

### 4. 填写应用 ID 或链接

软件支持两种输入方式：

```text
9plm9xgg6vks
```

或：

```text
https://apps.microsoft.com/detail/9plm9xgg6vks
```

### 5. 选择架构

根据当前系统选择对应架构：

- 大多数 64 位 Windows 电脑选择 `x64`。
- 32 位 Windows 选择 `x86`。
- ARM 设备选择 `arm64` 或 `arm`。

不确定时，通常可以先选择 `x64`。

### 6. 选择下载目录

点击下载目录选择按钮，指定安装包保存位置。

建议为不同应用保留独立目录，方便后续查看历史版本。

### 7. 查询版本

点击查询后，软件会显示：

- 当前系统已安装版本。
- 云端可下载的最新版本。
- 本地目录中已经下载的安装包版本。

如果本地版本低于云端版本，可以继续下载最新安装包。

### 8. 下载安装包

确认应用信息和架构无误后，点击下载按钮。

下载过程中，软件会优先使用较适合大文件的下载方式；如果连接被重置或下载失败，会自动重试，并在必要时切换备用下载方式。

下载完成后，安装包会显示在本地已下载安装包列表中。

### 9. 安装或更新应用

选择需要安装的包后，点击“安装/更新”。

软件会在安装前尝试停止目标应用残留进程，然后再执行安装命令。安装完成后，可以重新查询版本确认结果。

### 10. 安装历史版本

在本地已下载安装包列表中，右键点击任意历史安装包，选择安装此包。

这个功能适合需要回退到旧版本，或手动安装指定版本的场景。

### 11. 检查本软件更新

进入“关于”页面，点击“检查更新”。

软件会显示当前版本、GitHub 最新版本、更新文件和更新日志。需要更新时，可以点击“下载更新”，下载完成后点击“安装更新”。

### 12. 常见问题

#### 无法识别应用 ID

请确认输入的是 Microsoft Store 应用详情页中的应用 ID，或完整应用详情页链接。

#### 查询不到云端版本

可能原因包括：

- 应用不是免费公开应用。
- 应用存在区域限制。
- 网络无法访问相关下载服务。
- Microsoft Store 页面或服务返回结果发生变化。

#### 下载速度慢

可能原因包括：

- 当前 Microsoft 下载节点速度较慢。
- 网络线路到 Microsoft 下载服务不稳定。
- 系统代理或网络代理影响了下载连接。
- 杀毒软件或安全软件正在扫描大文件写入。
- 下载目录所在磁盘写入速度较慢。

可以尝试更换网络、关闭不必要的代理、换一个下载目录，或稍后重试。

#### 下载失败

请检查：

- 当前网络是否正常。
- 下载目录是否有写入权限。
- 磁盘空间是否充足。
- 杀毒软件是否拦截下载。

新版会在下载失败时自动重试，并在必要时切换备用下载方式。

#### 安装失败

请查看软件显示的错误信息。常见原因包括：

- 没有管理员权限。
- 系统不允许安装 AppX/MSIX。
- 安装包缺少依赖。
- Windows 版本不满足应用要求。
- 旧版本残留进程仍在运行。

#### Windows Server 无法使用 Microsoft Store

这是本工具适合的使用场景之一。只要系统支持 AppX/MSIX 安装，通常可以通过本工具下载并安装免费公开应用。

## English

### 1. Download

Open the [Releases page](https://github.com/zuelu/msstore-msix-manager/releases/latest) and download:

```text
MSStoreMsixManager.exe
```

After downloading, you can place the file in any convenient folder, for example:

```text
D:\Tools\MSStoreMsixManager\
```

### 2. Start The App

Double-click `MSStoreMsixManager.exe` to start.

If you meet permission issues while installing or updating apps, right-click the file and choose Run as administrator.

### 3. Choose Interface Language

The main interface supports Simplified Chinese and English. Use the language dropdown to switch. After switching, the management page, About page, log messages, and app-owned error messages will use the selected language.

### 4. Enter App ID Or Link

The app supports both formats:

```text
9plm9xgg6vks
```

or:

```text
https://apps.microsoft.com/detail/9plm9xgg6vks
```

### 5. Choose Architecture

Choose the architecture that matches your system:

- Most 64-bit Windows PCs use `x64`.
- 32-bit Windows uses `x86`.
- ARM devices use `arm64` or `arm`.

If you are not sure, try `x64` first.

### 6. Choose Download Folder

Click the download folder button and choose where packages should be saved.

Using a separate folder for each app is recommended, so older versions are easier to find later.

### 7. Check Versions

After clicking Check versions, the app shows:

- The currently installed version.
- The latest version available from the cloud.
- The latest downloaded package version in the local folder.

If the local version is older than the cloud version, you can download the latest package.

### 8. Download Package

After confirming the app information and architecture, click Download.

The app uses a download method suitable for large files first. If the connection is reset or the download fails, it retries automatically and switches to a fallback download method when needed.

When the download completes, the package appears in the local downloaded package list.

### 9. Install Or Update App

Select the package and click Install/Update.

Before installation, the app tries to stop residual processes for the target app, then runs the installation command. After installation, you can check versions again to confirm the result.

### 10. Install Historical Versions

Right-click any package in the local downloaded package list and choose to install it.

This is useful when you need to roll back to an older version or install a specific version manually.

### 11. Check Updates For This Tool

Open the About page and click Check for updates.

The app shows the current version, latest GitHub version, update file, and release notes. When an update is available, click Download update, then click Install update after the download completes.

### 12. FAQ

#### App ID Cannot Be Recognized

Make sure the input is a Microsoft Store app ID from the app details page, or a full app details link.

#### Cloud Version Cannot Be Found

Possible reasons:

- The app is not a free public app.
- The app is region-restricted.
- The network cannot access the required download services.
- Microsoft Store page structure or service response has changed.

#### Download Is Slow

Possible reasons:

- The current Microsoft download node is slow.
- The network route to Microsoft download services is unstable.
- System proxy or network proxy settings affect the download connection.
- Antivirus or security software is scanning large file writes.
- The selected download folder is on a slow disk.

You can try another network, disable unnecessary proxy settings, choose another download folder, or retry later.

#### Download Failed

Check:

- Network connection.
- Write permission for the download folder.
- Available disk space.
- Antivirus or security software blocking the download.

Newer versions retry automatically after download failures and switch to a fallback download method when needed.

#### Installation Failed

Read the error message shown by the app. Common reasons include:

- Missing administrator permission.
- System policy blocks AppX/MSIX installation.
- Missing dependency packages.
- Windows version does not meet the app requirements.
- Old residual processes are still running.

#### Microsoft Store Is Not Available On Windows Server

This is one of the main use cases for this tool. As long as the system supports AppX/MSIX installation, this tool can usually download and install free public apps.
