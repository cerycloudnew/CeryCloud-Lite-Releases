# CeryCloud Lite 官方发布

**官方网站：[cerycloud.com](https://cerycloud.com)**

CeryCloud Lite 官方安装包发布仓库。本仓库仅包含发布说明，不包含客户端源码；安装包与校验文件位于 Releases。

## 下载 4.0.1

**[查看最新发布与说明](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/tag/v4.0.1)** · [历史版本](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases)

| 系统 | 下载 |
| --- | --- |
| Windows x64 安装版 | [CeryCloud-Lite-4.0.1-windows-x64-setup.exe](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/download/v4.0.1/CeryCloud-Lite-4.0.1-windows-x64-setup.exe) |
| Windows x64 便携版 | [CeryCloud-Lite-4.0.1-windows-x64-portable.zip](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/download/v4.0.1/CeryCloud-Lite-4.0.1-windows-x64-portable.zip) |
| Android ARM64（主推） | [CeryCloud-Lite-4.0.1-android-arm64-v8a.apk](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/download/v4.0.1/CeryCloud-Lite-4.0.1-android-arm64-v8a.apk) |
| Android ARMv7 | [CeryCloud-Lite-4.0.1-android-armeabi-v7a.apk](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/download/v4.0.1/CeryCloud-Lite-4.0.1-android-armeabi-v7a.apk) |
| Android x86_64 | [CeryCloud-Lite-4.0.1-android-x86_64.apk](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/download/v4.0.1/CeryCloud-Lite-4.0.1-android-x86_64.apk) |
| macOS Apple 芯片 | [CeryCloud-Lite-4.0.1-macos-arm64.dmg](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/download/v4.0.1/CeryCloud-Lite-4.0.1-macos-arm64.dmg) |
| macOS Intel | [CeryCloud-Lite-4.0.1-macos-x64.dmg](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/download/v4.0.1/CeryCloud-Lite-4.0.1-macos-x64.dmg) |
| Linux x64 AppImage | [CeryCloud-Lite-4.0.1-linux-x64.AppImage](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/download/v4.0.1/CeryCloud-Lite-4.0.1-linux-x64.AppImage) |
| Linux AMD64 Debian / Ubuntu | [CeryCloud-Lite-4.0.1-linux-amd64.deb](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/download/v4.0.1/CeryCloud-Lite-4.0.1-linux-amd64.deb) |
| Linux x86_64 RPM | [CeryCloud-Lite-4.0.1-linux-x86_64.rpm](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/download/v4.0.1/CeryCloud-Lite-4.0.1-linux-x86_64.rpm) |

Android TV 按设备 CPU 架构选择同一个 Android 包；ARM64 电视使用 ARM64 APK。Android 沿用原包名及原正式 Release 签名。
Windows 便携版请完整解压，保留内核、资源和许可证。
当前十种成品不包含 Linux 无桌面 Server 安装包。

## 更新与验证范围

4.0.1 修复桌面延迟测量口径，并支持可选的构建时固定邀请码；本批普通发行包未配置内置邀请码。
版本统一为 4.0.1，完整源码提交标识、各文件 SHA-256 及实际测试边界见发布附件。

本轮为定向回归，没有对每个当前成品重跑完整原生测试；Windows 普通用户 GUI/UAC 弹窗未在本轮重新验证。
Mac 两架构 DMG 已构建和挂载校验，但使用 **ad-hoc 签名，未取得 Developer ID 签名或 Apple 公证**，没有实体 Intel Mac 验收，系统可能阻止首次打开。
详见发布页 `README.md`、`BUILD-INFO.json`、`ACCEPTANCE.json`；不保证所有设备、系统版本、节点和网络均通过。

## 校验与反馈

下载后使用发布页的 `SHA256SUMS.txt` 核对文件。GitHub 自动生成的 “Source code” 压缩文件仅包含本仓库说明，不是客户端安装包。
安装包保留第三方许可证，本仓库不包含签名私钥、账号凭据或含密订阅。
问题反馈：[Issues](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/issues)。请勿公开密码、认证信息或订阅链接。

官网：[https://cerycloud.com](https://cerycloud.com)
