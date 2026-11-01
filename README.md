# 社团学习与训练提交仓库

欢迎来到 **Club Learning Hub**！这里用来收集社团成员的日常学习成果、交流训练思路，并练习使用 GitHub 协作。

**不必等到完成一个大项目才提交。写懂一道题、整理一页笔记、解决一个报错，都是值得记录的进步。**

仓库地址：<https://github.com/magyyds/club-learning-hub>

## 可以提交什么？

| 内容 | 示例 |
| --- | --- |
| 代码练习 | 课堂练习、算法题、小工具、网页、课程项目 |
| 学习笔记 | 语言基础、知识梳理、读书笔记、命令速查 |
| 截图与演示 | 程序运行结果、实验过程、界面截图 |
| 复盘与总结 | 错题整理、调试记录、每周总结、学习计划 |
| 资料与问题 | 附个人理解的参考链接、暂未解决的问题 |

不限语言、技术方向和文件类型。代码可以是未完成的尝试，请说明当前状态；只有笔记或截图也可以提交。截图请配上简短说明，写清楚内容、操作过程和收获。引用他人的代码或资料时，请注明出处。

## 成员目录

| 成员 | 提交入口 |
| --- | --- |
| 王中儒 | [王中儒/](./王中儒/) |
| 谢瑾萱 | [谢瑾萱/](./谢瑾萱/) |
| 党苑铭 | [党苑铭/](./党苑铭/) |
| 马英琪 | [马英琪/](./马英琪/) |

```text
club-learning-hub/
├── README.md                      # 仓库介绍与提交教程
├── CONTRIBUTING.md                # 提交约定与维护说明
├── 王中儒/
│   └── README.md
├── 谢瑾萱/
│   └── README.md
├── 党苑铭/
│   └── README.md
├── 马英琪/
│   └── README.md
├── templates/
│   └── 学习记录模板.md
└── .github/
    ├── pull_request_template.md
    └── ISSUE_TEMPLATE/
        └── question.md
```

请把个人成果放在自己的目录下，推荐按 `姓名/YYYY-MM-DD-主题/` 整理，例如：

```text
王中儒/2026-11-01-Python循环练习/
├── README.md         # 学了什么、如何运行、遇到的问题
├── main.py           # 代码（按需）
├── notes.md          # 笔记（按需）
└── images/
    └── result.png    # 截图（按需）
```

这些分类都是建议，不要求每次提交同时包含代码、笔记和截图。目录按姓名划分只是协作约定，**不是访问权限隔离**。

## GitHub 是什么？

Git 是记录文件修改历史的版本控制工具；GitHub 是基于 Git 的在线托管与协作平台。它既能保存代码，也能管理文档、图片等学习资料，让大家查看历史、讨论问题和审阅修改。

| 名称 | 含义与用法 |
| --- | --- |
| Repository / Repo（仓库） | 一个项目的文件、历史记录和协作空间 |
| README | 仓库首页说明，通常使用 Markdown 编写 |
| Commit（提交） | 保存一次修改记录，并写一句说明 |
| Branch（分支） | 一条独立的修改路线；本仓库用 `main` 保存已合并成果 |
| Fork | 在自己的 GitHub 账号下创建仓库副本，方便提出修改 |
| Clone | 把远程仓库下载为本地 Git 仓库，包含版本历史 |
| Push / Pull | 把本地提交上传到远程 / 将远程更新取回并整合到本地 |
| Pull Request / PR | 请求把某个分支的修改合并到目标仓库或分支 |
| Review / Merge | 审阅修改、提出反馈 / 把修改合并进去 |
| Issue | 提问、记录问题、讨论学习任务；不是提交文件的替代方式 |
| Star / Watch | 收藏仓库 / 设置仓库活动通知 |

打开仓库后，在 **Code** 浏览文件；在 **Pull requests** 提交和查看 PR；在 **Issues** 提问；在文件的 **History** 中查看修改历史。**Download ZIP** 适合下载阅读，想持续提交则建议 Fork 后 Clone。

## 提交路线一：只用网页（新手推荐）

流程：**Fork → 新建分支 → 上传到自己的目录 → Commit → PR → 等待审阅和合并。**

### 1. Fork 到自己的账号

登录 GitHub，打开本仓库，点击右上角 **Fork → Create fork**。完成后确认页面地址是 `你的用户名/club-learning-hub`。

此路线面向可以 Fork 的公开仓库。无需成为原仓库的协作者，也不需要原仓库写入权限。

### 2. 同步并创建本次提交分支

在自己的 Fork 切换到 `main`。后续提交前，先使用 **Sync fork → Update branch** 同步原仓库；首次 Fork 通常已是最新状态。若提示冲突，先处理冲突或在 Issue 中求助。

点击左上角分支选择器，输入一个新分支名，例如 `study/wangzhongru-20261101-python`，然后创建分支。每次独立的学习任务使用一个新分支，避免把多次作业混在同一个 PR 中。

### 3. 添加学习成果

进入自己的姓名目录，确认当前分支是刚创建的分支。

- **上传现有文件**：点击 **Add file → Upload files**，拖入本地整理好的主题文件夹及其内容。提交前检查页面上的文件路径。
- **在线写笔记**：点击 **Add file → Create new file**，在文件名中输入 `2026-11-01-Python循环练习/notes.md`，再填写内容。路径中的 `/` 可以创建子目录。
- 图片建议与相关笔记放在同一个主题目录中，例如 `images/result.png`，并在笔记中通过 `![运行结果](images/result.png)` 引用。

网页上传单个文件上限为 25 MiB，一次最多上传 100 个文件；更大的素材建议压缩或提供可访问的资料链接。详情见 [GitHub 文件上传文档](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)。

填写清晰的提交说明，例如 `docs: 王中儒补充 Python 循环笔记`，点击 **Commit changes**，保存到自己的任务分支。多次上传可以继续提交到同一分支。

### 4. 发起 PR

回到自己 Fork 的首页，选择本次任务分支，点击 **Contribute → Open pull request**。也可以在原仓库 **Pull requests → New pull request → compare across forks** 手动选择。

务必检查方向：

| 选项 | 应选择 |
| --- | --- |
| base repository（接收修改） | `magyyds/club-learning-hub` |
| base branch | `main` |
| head repository（提供修改） | `你的用户名/club-learning-hub` |
| compare branch | 你的本次任务分支 |

PR 标题建议使用 `姓名｜日期｜学习主题`，例如 `王中儒｜2026-11-01｜Python 循环练习`。

按自动出现的模板说明：提交了什么、学到了什么、如何运行或查看、是否有需要帮助的问题。在 **Files changed** 检查改动范围，确认后点击 **Create pull request**。

### 5. 根据反馈修改，等待合并

维护者会审阅你的 PR。需要补充时，继续修改并提交到**同一个 Fork 的同一个分支**，PR 会自动更新，不必重新创建。讨论中的未完成尝试也可以先创建 Draft PR，准备好后再标记为可审阅。

PR 显示 **Merged** 后，成果才正式进入原仓库 `main`。下一次提交前，再同步自己 Fork 的 `main` 并创建新分支。

## 提交路线二：Git 命令行

先安装 Git、注册并登录 GitHub，在网页上完成 Fork。以下命令在终端中逐行执行；将 `YOUR_USERNAME` 替换为你的 GitHub 用户名，将示例姓名、日期和主题替换为自己的信息。

### 1. 首次配置与克隆

```bash
# 仅首次需要：填写提交作者信息
git config --global user.name "你的名字"
git config --global user.email "你的提交邮箱"

# 克隆自己的 Fork，而不是原仓库
git clone https://github.com/YOUR_USERNAME/club-learning-hub.git
cd club-learning-hub

# origin 指向自己的 Fork；upstream 指向社团原仓库
git remote add upstream https://github.com/magyyds/club-learning-hub.git
git remote -v
```

可以使用 GitHub **Settings → Emails** 中提供的 `noreply` 邮箱作为提交邮箱。HTTPS 推送请使用 Git Credential Manager 的登录流程或其他受支持的认证方式；GitHub 账号密码不能直接用于 Git HTTPS 推送认证。

### 2. 每次训练前同步并建分支

先用 `git status` 确认工作区没有未处理的修改，再执行：

```bash
git switch main
git fetch upstream
git merge --ff-only upstream/main
git push origin main
git switch -c study/wangzhongru-20261101-python
```

如果 `--ff-only` 报错，说明本地 `main` 与上游出现分叉，请先检查历史或求助，不要直接强制覆盖。把日常修改放在任务分支中，可以减少这种情况。

### 3. 添加文件并推送

在文件管理器或编辑器中，把学习成果保存到自己的目录，例如 `王中儒/2026-11-01-Python循环练习/`。

```bash
git status
git add "王中儒/2026-11-01-Python循环练习/"
git diff --cached --stat
git diff --cached
git commit -m "docs: 王中儒提交 Python 循环学习记录"
git push -u origin study/wangzhongru-20261101-python
```

打开 GitHub 页面，按上面的网页教程发起 PR，目标为 `magyyds/club-learning-hub` 的 `main`。

收到修改意见后，在当前任务分支继续编辑，再执行：

```bash
git add "王中儒/2026-11-01-Python循环练习/"
git commit -m "docs: 补充运行说明与学习总结"
git push
```

## 提交约定

1. **主要修改自己的目录。** 公共文档改进可以单独提 PR；修改其他成员内容前先沟通。
2. **每次有一点说明。** 至少写清学习主题和本次收获；有代码时尽量附运行命令、依赖和示例输入输出。
3. **内容真实，允许不完美。** 可以记录失败尝试、问题和下一步计划；使用 AI 辅助时，建议说明自己理解、验证或修改了什么。
4. **文件保持清晰。** 使用有意义的名称，避免 `最终版2真的最终版`；不要提交依赖目录、缓存、编译产物和无关大文件。
5. **提交前检查内容。** 不要把密码、Token、个人证件、隐私聊天内容等混入代码或截图；引用资料保留来源。
6. **认真交流。** 针对代码和思路提出具体建议，尊重不同的学习进度。

更多说明见 [贡献指南](./CONTRIBUTING.md)，可复制 [学习记录模板](./templates/学习记录模板.md) 开始记录。

## 常见问题

**不会写代码，也能交吗？** 可以。笔记、截图、学习路线、课程总结和问题记录都欢迎。

**没有原仓库写权限怎么办？** 使用 Fork + PR。PR 是提出合并请求，不要求先获得原仓库写权限。

**为什么上传完了，原仓库里还看不到？** Commit 到 Fork 只改变你的副本；还需要发起 PR，并由维护者合并。

**PR 没有差异或方向不对怎么办？** 检查 base 是否为原仓库 `main`，compare 是否为自己已经提交并推送的任务分支。

**改了文件，但 PR 没更新怎么办？** 确认修改提交到了这个 PR 对应的分支；命令行操作还需要 `git push`。

**发生冲突怎么办？** 在 PR 中查看冲突文件，理解双方改动后处理；不确定时在 PR 评论或 Issue 中说明情况，请维护者协助，避免随意覆盖别人的内容。

**想加入新成员怎么办？** 新建自己的姓名目录与介绍，通过 PR 请求加入；重名时可以使用 `姓名-GitHub用户名`。

## 推荐的第一次提交

- 在自己的目录中新建 `YYYY-MM-DD-第一次提交/README.md`。
- 简单介绍自己的学习方向，记录今天学到的一个知识点。
- 可选：附上一段代码或一张截图。
- 发起第一个 PR，完成一次从记录到协作的练习。

## 官方入门资料

- [GitHub Hello World：仓库、分支、提交与 PR](https://docs.github.com/en/get-started/using-github/hello-world)
- [创建 Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)
- [从 Fork 创建 PR](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)
- [Markdown 基础语法](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Git 官方中文教程](https://git-scm.com/book/zh/v2)

持续记录，互相交流，让每一次练习都有迹可循。
