# FRC 编程环境与 GitHub 协作课堂

第一次接触编程工具，从安装检查开始。**环境截图必交，GitHub 的 Issue 和 PR 选做；遇到报错也能按实际进度交作业。**

| 你要做什么 | 入口 |
| --- | --- |
| 一份文件读完教程和作业 | **[完整合订版 Markdown](docs/FRC编程环境与GitHub协作_完整教程与作业.md)** |
| 跟着安装、操作 | [Markdown 教程，含 Windows / macOS 与真实 VS Code 示例图](docs/tutorial.md) |
| 找安装包与下载备用 | [软件下载清单](docs/downloads.md) |
| 看必交、选做和截图要求 | [作业页](ASSIGNMENT.md) |
| 交作业 | **[问卷星提交入口](https://v.wjx.cn/vm/YR3nxKS.aspx)** |
| 做 GitHub 练习 | [贡献步骤](CONTRIBUTING.md) · [文件示例](examples/FRC-EXAMPLE.md) |
| 检查公开信息 | [学习代号与隐私](PRIVACY.md) |

<a href="https://v.wjx.cn/vm/YR3nxKS.aspx"><img src="docs/assets/assignment-qrcode.jpg" alt="FRC 作业问卷星提交二维码" width="200"></a>

## 本课固定环境

- **WPILib `2027.0.0-alpha-6`**：课堂指定测试版，不代表最新或稳定版。
- Windows 11 x64，或 macOS 15 及以上；Mac 按 Apple 芯片 / Intel 选择安装包。本教程不适用 ARM Windows。
- 环境检查用配套 WPILib VS Code；Markdown 文字练习可用普通 VS Code。JDK 由 WPILib 安装器准备。

本仓库不是机器人控制工程，不要求连接、部署或驱动机器人。设备镜像、库与比赛环境由老师另外核对。

## 作业路线

1. 尝试安装，截取 Git 与 WPILib 检查结果；报错或卡住也保留画面。
2. 有余力再 Fork、Clone、写一个 Markdown 文件，提 Issue 和 PR。PR 不用等合并。
3. 在问卷填姓名、学号、自选随机代号和系统，上传必交截图。三道 GitHub 截图题可留空，不另写报告。

代号格式是 `FRC-` 加 8 位随机数字，自己选，不找老师领取，不用学号或生日。公开 GitHub 只用代号与昵称；姓名、学号只填给老师的问卷。截图不上传仓库，提交身份与邮箱也要按隐私说明检查。

## 仓库结构

```text
docs/tutorial.md   学生主教程，Markdown 版
docs/downloads.md  下载地址与校验方法
docs/assets/       教程示例图和提交二维码
ASSIGNMENT.md      作业与问卷题目清单
examples/         只读练习示例
submissions/      每人只新增自己的代号文件
.github/          Issue 与 PR 模板
```

教程与作业以 Markdown 为准，便于阅读、搜索和复制命令。旧 Word 文档保留为历史版本，未同步本次提交规则，请勿据此交作业。

没有配置 GitHub Actions，不需要上传凭据或开放额外权限。不要把整个电脑工作目录或机器人工程复制到这里。
