# 微软商店 MSIX 管理器

微软商店 MSIX 管理器是一款面向 Windows 用户的免费工具，适用于 Windows Server、精简版 Windows 或无法直接使用 Microsoft Store 的环境。它可以帮助用户通过 Microsoft Store 应用 ID 或应用链接查询、下载并安装免费公开应用的 MSIX/AppX 安装包。

## 主要功能

- 支持输入 Microsoft Store 应用 ID 或完整应用链接。
- 支持选择下载架构：x64、x86、arm64、arm。
- 支持指定安装包下载目录。
- 支持对比已安装版本、云端最新版本和本地已下载版本。
- 支持下载免费公开应用的 MSIX/AppX 安装包。
- 支持点击按钮后手动执行安装或更新。
- 支持在本地历史安装包列表中右键安装任意历史版本。
- 支持自动识别并处理常见依赖包。
- 安装前会尝试停止目标应用残留进程，减少安装失败。
- 安装失败时会显示明确的诊断信息，方便排查。

## 下载

请前往 [Releases 页面](https://github.com/zuelu/msstore-msix-manager/releases/latest) 下载：

`MSStoreMsixManager.exe`

下载后双击运行即可。

## 基本使用

1. 打开 `MSStoreMsixManager.exe`。
2. 在应用 ID 输入框中填写 Microsoft Store 应用 ID，或粘贴完整应用链接。
3. 选择需要下载的架构。
4. 选择安装包保存目录。
5. 点击查询，查看已安装版本、云端最新版本和本地已下载版本。
6. 需要下载时，点击下载按钮。
7. 需要安装或更新时，点击“安装/更新”按钮。
8. 如需安装历史版本，可在本地已下载安装包列表中右键选择安装。

更详细的步骤请查看 [安装使用说明](./INSTALL.md)。

## 如何获取应用 ID

1. 打开 [Microsoft Store 网页版](https://apps.microsoft.com/)。
2. 搜索需要下载的应用。
3. 进入应用详情页。
4. 复制链接中的应用 ID。

示例：

```text
https://apps.microsoft.com/detail/9plm9xgg6vks
```

其中 `9plm9xgg6vks` 就是应用 ID。

## 注意事项

- 本工具主要用于 Microsoft Store 中的免费公开应用。
- 付费应用、私有应用、区域受限应用或需要特殊许可证的应用，可能无法下载或安装。
- MSIX/AppX 应用的实际安装位置由 Windows 系统管理。
- 安装或更新应用时，建议使用管理员权限运行本工具。
- 如果系统策略限制 AppX/MSIX 安装，需要先调整系统策略后再使用。

## 更新日志

请查看 [CHANGELOG.md](./CHANGELOG.md)。

## 作者信息

作者：云遮天  
Telegram：[@czzzru](https://t.me/czzzru)  
QQ：80795151  
网站：[https://czzz.ru](https://czzz.ru)
