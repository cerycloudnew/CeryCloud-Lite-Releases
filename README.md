# CeryCloud Lite 官方发布

**官方网站：[cerycloud.com](https://cerycloud.com)**

这里是 CeryCloud Lite 的官方安装包发布仓库，提供 Windows、Android、Linux 和 macOS 版本。

本仓库仅用于发布安装包、安装说明与校验文件，不包含客户端源代码。

## 下载

**[前往 Releases 下载](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/releases)**

请在发布页的 **Assets** 中选择对应系统和架构的安装包。不要下载 GitHub 自动生成的 “Source code” 压缩文件，它们仅包含本仓库说明文件，不是客户端。

| 系统 | 选择版本 | 安装方法 |
| --- | --- | --- |
| Windows | `windows-x64.zip` | 解压整个目录，运行 `cerycloud-lite.exe`；保留同目录的 `mihomo.exe` 和许可证，需要 WebView2 Runtime。 |
| Android 手机 | `android-arm64-debug.apk` | 下载 APK，允许该下载来源安装应用后打开安装。 |
| Android x86_64 设备/模拟器 | `android-x86_64-debug.apk` | 选择与你设备架构相符的 APK。 |
| Linux 桌面 | `linux-desktop-x64.tar.gz` | 解压后运行 `cerycloud-lite`，需桌面环境及 GTK/WebKitGTK 4.1 等依赖。 |
| Linux 无桌面服务器 | `linux-server-x64.tar.gz` | 提供守护程序、CLI 和本机网页管理；使用方法见包内说明。 |
| macOS M 系列芯片 | `macos-arm64.dmg` | 打开 DMG，把 CeryCloud Lite.app 拖到 Applications。 |
| macOS Intel 芯片 | `macos-x86_64.dmg` | 同上；可在“关于本机”查看芯片类型。 |

## 当前版本说明

当前发布为 **0.1.0 测试版**，请阅读对应 Release 的已验证范围与限制。

- macOS 使用 ad-hoc 临时签名，尚未取得 Developer ID 签名及 Apple 公证。如果系统仅因开发者身份未验证而阻止打开，在确认来源和校验值后，可到“系统设置 → 隐私与安全性 → 仍要打开”确认。无需关闭全局安全保护；TUN 权限仍需单独授权。详见 [Apple 官方说明](https://support.apple.com/zh-cn/102445)。
- Android 当前为调试签名候选包；若已有不同签名版本，可能不能直接覆盖安装。卸载可能清除数据，请先做好备份。
- Linux 提供桌面和无桌面 Server 两种版本。Server 管理页面默认只监听本机，远程访问应使用 SSH 隧道。
- macOS 真实用户设备的交互式安装/授权、Android ARM64 真机及全部 Linux 发行版尚未完成覆盖验证。测试版不代表这些场景已经全部验收。

## 文件校验与反馈

每次发布附带 `SHA256SUMS.txt`，可用于核对下载文件的完整性。安装包内保留相关第三方许可证。

遇到问题可在本仓库 [Issues](https://github.com/cerycloudnew/CeryCloud-Lite-Releases/issues) 提交系统版本、客户端版本和错误信息。请勿公开密码、认证信息、订阅链接或账号隐私。

官网：[https://cerycloud.com](https://cerycloud.com)
