# CeryCloud Lite

官网：[cerycloud.com](https://cerycloud.com) · [下载最新版本](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/latest)

在发行页的 Assets 中选择对应系统安装包，安装前按 `SHA256SUMS.txt` 核对文件名和 SHA-256。具体安装方法见该版本的 `README` 或 `INSTALL` 附件。

| 系统 | 选择 |
| --- | --- |
| Windows x64 | `.exe` 安装版，或完整解压 `.zip` 便携版后运行 |
| Android / Android TV | 优先选择设备支持的 ARM64 APK，其他设备按架构选择 ARMv7 或 x86_64 |
| macOS | Apple 芯片选择 ARM64，Intel 芯片选择 x64 / x86_64；打开 DMG 后拖入“应用程序” |
| Linux x64 | Debian / Ubuntu 选择 DEB，Fedora / RHEL 选择 RPM，通用桌面版选择 AppImage |
| Linux Server x64 | 无图形界面后台服务，选择 `linux-server-x64.tar.gz` |

Android 正式版通常可直接覆盖升级；从 0.1.0 测试版迁移到正式版需先备份本地设置并卸载旧版，卸载会清除本地数据。macOS 如被系统阻止，请核对下载来源及校验值后，按照“隐私与安全性”中的提示处理。

校验示例：Windows 使用 `Get-FileHash -Algorithm SHA256 文件名`，macOS 使用 `shasum -a 256 文件名`，Linux 使用 `sha256sum 文件名`。

GitHub 自动生成的 Source code 压缩文件不是客户端安装包。
