# CeryCloud Lite 官方发布

**官方网站：[cerycloud.com](https://cerycloud.com)**

CeryCloud Lite 的官方安装包发布仓库，提供 Windows、Android、Linux 和 macOS 版本。本仓库仅包含发布说明，安装包和校验文件位于 Releases，不包含客户端源码。

## 下载 4.0.0

**[下载最新版本](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases/latest)** · [历史版本](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases)

请在发布页的 **Assets** 中下载对应安装包。GitHub 自动生成的 “Source code” 压缩文件只包含本仓库说明，不是安装包。

| 系统 | 选择版本 | 安装方法 |
| --- | --- | --- |
| Windows | `windows-x64.zip` | 解压整个目录，运行 cerycloud-lite.exe，保留内核和许可证。需要 WebView2 Runtime。 |
| Android 手机 | `android-arm64.apk` | 大多数手机选择 ARM64，下载后打开 APK 安装。 |
| Android x86_64 | `android-x86_64.apk` | 用于 x86_64 设备/模拟器。 |
| Linux 桌面 | `linux-desktop-x64.tar.gz` | 解压后运行 cerycloud-lite，需要桌面环境及 GTK/WebKitGTK 4.1 等依赖。 |
| Linux Server | `linux-server-x64.tar.gz` | 无桌面后台服务、CLI 和本机网页管理，详见发布页 INSTALL.md。 |
| macOS M 系列芯片 | `macos-arm64.dmg` | 打开 DMG，把 CeryCloud Lite.app 拖入 Applications。 |
| macOS Intel | `macos-x86_64.dmg` | 同上，可在“关于本机”查看芯片类型。 |

## Android 升级说明

4.0.0 使用长期正式发布签名，并关闭调试功能。之前的 0.1.0 调试签名包不能直接覆盖升级；请先备份本地设置，卸载旧版后安装并重新登录。卸载会清除旧版应用数据，后续正式版本复用同一发布签名。

## macOS 安装说明

当前 macOS 包使用 ad-hoc 临时签名，未取得 Developer ID 签名或 Apple 公证。如果系统仅因开发者身份未验证而阻止打开，在确认来源及文件校验值后，可到“系统设置 → 隐私与安全性 → 仍要打开”确认，无需关闭全局安全保护。

如果提示文件已损坏或包含恶意软件，请先检查下载完整性并反馈具体提示。TUN 仍需单独系统授权。[Apple 官方说明](https://support.apple.com/zh-cn/102445)

## 校验与反馈

每次发布附带 SHA256SUMS.txt。安装包保留第三方许可证。各平台的验证范围详见对应 Release，不代表覆盖所有设备、网络和系统版本。

遇到问题可在 [Issues](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/issues) 提交系统版本、应用版本与错误信息，请勿公开密码、认证信息或订阅链接。

官网：[https://cerycloud.com](https://cerycloud.com)
