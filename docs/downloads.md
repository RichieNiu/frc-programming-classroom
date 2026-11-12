# 软件下载地址

核对日期：2026-11-12。先按电脑系统和芯片选文件。WPILib 固定为课堂用 Alpha 6，普通 VS Code 和 Git 不要求全班的小版本完全一致。

## WPILib 课堂版本

官方发布页：
https://github.com/wpilibsuite/allwpilib/releases/tag/v2027.0.0-alpha-6

Windows 11 x64 官方直链：
https://packages.wpilib.workers.dev/installer/v2027.0.0-alpha-6/Win64/WPILib_Windows-2027.0.0-alpha-6.iso

Mac Apple 芯片官方直链：
https://packages.wpilib.workers.dev/installer/v2027.0.0-alpha-6/macOSArm/WPILib_macOS-Arm64-2027.0.0-alpha-6.dmg

Mac Intel 官方直链：
https://packages.wpilib.workers.dev/installer/v2027.0.0-alpha-6/macOS/WPILib_macOS-Intel-2027.0.0-alpha-6.dmg

Mac 要求 macOS 15 或以上，安装器运行前需装好 Xcode Command Line Tools。Windows 要求 64 位 Windows 11，ARM Windows 不支持。系统不符合时先找老师，不自行升级学校电脑。

### Alpha 6 官方 SHA256

Windows ISO：
`3f1c9f921c3747d8bbc3d36da6603c750ed2e04a27a1f4a6ae87c529d4f3144e`

Mac Intel DMG：
`d2914b53f252f740ad848cca5f695c90234b2d40df71fd994330d14fe6a3be79`

Mac Arm64 DMG：
`f6c9b5291ac383db082a45856a480a8dbe8c906696c3c960048547c579a1e2bf`

校验值抄自上述官方发布页。下载后按同名文件逐位核对，不把 Intel 与 Arm64 混用。

## 普通 VS Code

官方下载安装页：
https://code.visualstudio.com/Download

Windows 选 x64；Mac 按芯片选 Apple silicon 或 Intel。普通 VS Code 可以完成本次文字作业，但不代替 WPILib 配套环境。

## Git

Windows 官方入口：
https://git-scm.com/install/windows

本次核对到的 Git 2.56.1 x64 官方安装包：
https://github.com/git-for-windows/git/releases/download/v2.56.1.windows.1/Git-2.56.1-64-bit.exe

Mac 官方说明：
https://git-scm.com/install/mac

Mac 先运行 `git --version`。已安装就不重复装；没有时按官方说明安装 Xcode Command Line Tools。本次不用先装 Homebrew。

## GitHub 文件加速备用

第三方入口：
https://ghfast.top/
https://gh-proxy.com/

Git 2.56.1 x64 加速示例：
https://ghfast.top/https://github.com/git-for-windows/git/releases/download/v2.56.1.windows.1/Git-2.56.1-64-bit.exe
https://gh-proxy.com/https://github.com/git-for-windows/git/releases/download/v2.56.1.windows.1/Git-2.56.1-64-bit.exe

2026-11-12 从老师当前网络核对时，两处入口和代理的公开 README 小文件都能访问，且内容与原文件一致。没有完成课堂批量下载测试，不承诺速度、可用性或安装包安全性。

这些站点只作为公开文件下载备用，不是 GitHub 或学校的服务。仅在学校允许时使用。不要在站点登录，不提交密码、验证码、Token、私有仓库链接或个人资料，不用它们 Push 或提交作业。

WPILib 安装包已使用官方发布页指向的 `packages.wpilib.workers.dev`。不要给这些非 GitHub 地址硬加 GitHub 加速前缀。

下载后核对官方校验值或发布者签名。遇到证书警告、另装插件、关闭防护、付费解锁等要求就停止，改用官方入口或请老师提供离线材料。
