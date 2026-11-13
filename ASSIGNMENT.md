# 作业：环境安装与 GitHub 协作

[安装与操作教程](docs/tutorial.md) | [软件下载](docs/downloads.md) | **[打开问卷星交作业](https://v.wjx.cn/vm/YR3nxKS.aspx)**

**必交：环境检查或尝试过程截图。选做：Issue 和 PR。** 安装报错、步骤卡住、不会 GitHub，都可以按实际进度提交。不另交 Word、PDF 或实验报告。

<a href="https://v.wjx.cn/vm/YR3nxKS.aspx"><img src="docs/assets/assignment-qrcode.jpg" alt="FRC 作业问卷星提交二维码" width="220"></a>

扫码与文字链接是同一入口。电脑可直接点击，手机可扫码上传截图。

## 1. 先选一个学习代号

格式为 `FRC-` 加 **8 位随机数字**，自己选，不用找老师领取。不要用生日、学号、班级座号或电话尾号。教程里的 `FRC-58320491` 是老师示例，不要照抄。

GitHub 用户名自己起昵称。做 GitHub 选做时，先在教师仓库 `submissions` 和 Issues 搜索代号，重号就换一个；文件、分支、Issue、PR 和问卷用同一代号。

姓名和学号只填给老师的问卷，不写进公开 GitHub、截图内容或文件名。代号不保证匿名，公开账号资料仍可能关联身份。

## 2. 必做：尝试安装与环境检查

按[教程第 2 至 4 节](docs/tutorial.md#download)安装课堂指定的 WPILib `2027.0.0-alpha-6` 和 Git。Windows 11 x64 与 macOS 路线不同，先确认系统和芯片。

检查时打开 **WPILib 配套 VS Code**：

1. 在终端执行下面的命令，查看 Git 版本。
2. 在扩展面板搜索 `@installed WPILib`，确认扩展已启用。
3. 打开命令面板搜索 `WPILib`，检查能否找到 WPILib 命令，不必创建项目。

```sh
git --version
```

成功时截取“Git 版本 + WPILib 命令面板”。没成功时截取清楚的报错或卡住步骤，**不用等全部装好才交**。本次不要求构建、连接或部署机器人。

## 3. 选做：Issue 与 PR

完整操作与真实 VS Code 示例图见[教程第 5 节](docs/tutorial.md#github)。可分项尝试，没完成的截图题留空。

| 任务 | 操作与检查 |
| --- | --- |
| Issue | 在[教师仓库 Issues](https://github.com/ZaneZhang-MINXIN/frc-programming-classroom/issues)选“课堂提问或建议”，用代号提出真实问题或具体建议；不编造故障 |
| PR | Fork 教师仓库，Clone 自己的 Fork，创建 `practice/自己的代号`，新增 `submissions/自己的代号.md`，Commit 后 Push |
| PR 方向 | base 为 `ZaneZhang-MINXIN/frc-programming-classroom` 的 `main`；head 为自己 Fork 的练习分支 |
| 文件范围 | Files changed 只出现自己的一个 `.md` 文件；不改其他同学文件、教程或模板 |

练习文件写代号和一句**实际学到的操作**，例如：

```markdown
# FRC-58320491 的第一次协作练习

我学会了先保存文件，再暂存和提交。
```

替换示例代号和句子。PR 有关联 Issue 就填链接，暂未做 Issue 就如实注明。PR 为 Open 或 Merged 都可以交截图，不必等回复、合并或关闭。

## 4. 按问卷题目准备截图

Windows 用 `Win + Shift + S`，Mac 用 `Command + Shift + 4`。每道上传题 **最多 1 个文件、最大 10 MB，格式仅 PNG / JPG / JPEG**。

| 题号 | 问卷内容 | 是否必填 | 填写 / 截图要求 |
| --- | --- | --- | --- |
| 1 | 你的姓名 | 是 | 填真实姓名，仅供老师认领作业 |
| 2 | 你的学号 | 是 | 保留开头的 `0`，不要改成学习代号 |
| 3 | 本次作业的学习代号 | 是 | 自选 `FRC-` 加 8 位随机数字 |
| 4 | 这次作业使用的电脑系统 | 是 | Windows 11 x64 / Mac Apple 芯片 / Mac Intel / 其他或不确定 |
| 5 | 环境检查截图 | 是 | 成功：Git 版本与 WPILib 命令；未成功：报错或卡住步骤 |
| 6 | Issue 截图 | 否，选做 | 教师仓库名称、Issue 标题与编号、代号及问题内容 |
| 7 | PR 概览截图 | 否，选做 | 教师仓库名称、PR 标题与编号、代号、状态及合并方向 |
| 8 | PR 文件差异截图 | 否，选做 | PR 网页的 **Files changed**，只改自己的文件，内容清楚；不是本地编辑器截图 |
| 9 | 提交确认 | 是 | 先检查实际进度与隐私，再勾选；不要求声称已完成 GitHub |
| 10 | 补充截图 | 否 | 一张图放不下或需要说明时使用 |

文件名可用 `自己的代号-环境.png`、`自己的代号-Issue.png`、`自己的代号-PR.png`、`自己的代号-差异.png`。不要上传安装包，不把多张截图缩成看不清的长图。

## 5. 提交前逐项检查

- [ ] 姓名、学号、学习代号填写正确，学号没有丢开头的 `0`。
- [ ] 第 5 题有自己的真实进度截图；尚未成功也可提交。
- [ ] 第 6 至 8 题按实际完成情况上传，不借用同学的记录或截图。
- [ ] 图中文字清楚，裁掉无关窗口与标签页，遮盖个人路径、邮箱、密码、验证码或 Token。
- [ ] 截图只交问卷，没有传到 GitHub、Issue、PR 或公开 Fork。

**[现在提交问卷](https://v.wjx.cn/vm/YR3nxKS.aspx)**。点击提交并看到成功提示后，保留原始截图；提交成功不代表已经批改，补交与截止安排按老师通知。
