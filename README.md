# FRC 编程环境与 GitHub 协作课堂

面向第一次接触编程工具的学生。先装好课堂指定的 WPILib 和 Git，再完成一次 Fork、分支、提交、Issue 与 Pull Request 练习。

**课堂入口：** https://github.com/ZaneZhang-MINXIN/frc-programming-classroom

## 从这里开始

- [完整教程](docs/tutorial.md)
- [软件下载直链和加速备用](docs/downloads.md)
- [可编辑 Word 教程](docs/FRC编程环境安装与GitHub协作详细教程.docx)
- [最后的作业与截图要求](ASSIGNMENT.md)
- [贡献步骤](CONTRIBUTING.md)
- [隐私与学习代号](PRIVACY.md)
- [练习文件示例](examples/FRC-EXAMPLE.md)

## 本课固定环境

- Windows 11 x64，或 macOS 15 及以上的 Mac；Mac 按 Apple 芯片或 Intel 选择安装包。
- WPILib `2027.0.0-alpha-6`，含配套 VS Code、JDK 与开发工具。
- Windows 安装 Git for Windows；Mac 先检查 Git，需要时安装 Xcode Command Line Tools。GitHub 使用自己的课堂账号。

机器人环境检查用配套 WPILib VS Code；本次文字作业可以用普通 VS Code。教程附有老师在本机普通 VS Code 中的实拍示例。

Alpha 6 是课堂指定测试版，不代表最新版本或正式稳定版。ARM Windows 不按本教程安装。机器人硬件、系统镜像与厂商库须由老师核对；本仓库不提供机器人控制工程，不要求连接或驱动机器人。

## 作业做什么

1. 完成环境检查。
2. Fork 本仓库，在自己的分支新增 `submissions/你的学习代号.md`，向本仓库提交一个 PR。
3. 在本仓库提交一个真实问题或具体建议的 Issue。
4. 准备环境、Issue、PR 概览和 Files changed 四张截图。等老师公布问卷星入口后逐题上传，不另写报告。

PR 可以保持 Open，Issue 也可以保持 Open。老师尚未回复或合并，不影响学生完成提交。

## 公开前先检查

GitHub 用户名自己起昵称，学习代号也自己选，格式为 `FRC-` 加 8 位随机数字，例如 `FRC-58320491`，不要照抄示例。到 `submissions` 和 Issues 搜索是否重号，有人用了就换一个。不需要找老师领取。

不要公开真实姓名、学号、班级名单、生日、电话、私人邮箱、密码、令牌或身份对应表。代号不保证匿名，GitHub 用户名、公开资料、提交历史和活动仍可能关联身份。

学号只填在老师指定的非公开问卷中。截图不要放进本仓库、Issue、PR 或自己的公开 Fork。提交前裁掉无关窗口，遮盖路径中的真实姓名等内容。

## 仓库结构

```text
docs/           完整教程和 Word 文档
examples/       只读的练习示例
submissions/    每位学生只新增自己的代号文件
.github/        Issue 和 PR 模板
```

没有设置 GitHub Actions，不需要学生上传凭据或开放额外权限。请不要把电脑上的整个工作目录或机器人项目复制到这里。
