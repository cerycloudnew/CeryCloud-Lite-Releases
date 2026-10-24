# CeryCloud Lite 官方发布

官网：[cerycloud.com](https://cerycloud.com)

本仓库只发布官方安装包、校验清单与安装说明，不包含客户端源码或签名私钥。

[下载最新版 4.0.2](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/tag/v4.0.2)

| 系统 | 安装包 |
| --- | --- |
| Windows x64 / AMD64 | `.exe` 安装版、`.zip` 便携版 |
| Android / Android TV | ARM64（主推）、ARMv7、x86_64 APK |
| macOS | Apple ARM64、Intel x64 DMG |
| Linux x64 / AMD64 | AppImage、DEB、RPM |

Android TV 使用对应架构的同一份 Android APK。Android 保持原包名与正式 Release 签名，覆盖升级时不要先卸载。

安装前请阅读发布资产 `README.txt`，并按 `SHA256SUMS.txt` 核对完整文件名及 SHA-256。实际检查范围见 `ACCEPTANCE.json`，构建来源见 `BUILD-INFO.json`。

macOS 沿用 ad-hoc 签名，没有 Developer ID 与 Apple 公证，可能需要在系统“隐私与安全性”中对本应用确认打开；不要全局关闭 Gatekeeper。

应用内更新只在用户确认后安装，仍遵守各系统权限要求。后端版本配置由运营方独立启用。

GitHub 自动生成的 Source code ZIP/TAR 只含本发布仓库文档，不是客户端安装包。
