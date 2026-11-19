# Git 学习仓库

这是我学习 Git 的实操记录仓库，用一条"水果清单"把 Git 的核心操作全走了一遍。

## 学到了什么

| 操作 | 命令 | 说明 |
| --- | --- | --- |
| 初始化 | `git init` | 建仓库 |
| 提交 | `git add` + `git commit` | 挑选 + 存档 |
| 查看 | `git status` / `git diff` / `git log` | 状态、差异、历史 |
| 撤销 | `git restore` / `git reset` / `git revert` | 三种撤销方式 |
| 分支 | `git switch -c` / `git merge` | 并行开发 |
| 冲突 | 手动编辑 + `git add` + `commit` | 解决同一行的冲突 |
| 标签 | `git tag -a` | 给版本钉钉子 |
| 远端 | `git push` / `git pull` / `git clone` | 上传和拉取 |

## 分支说明

| 分支 | 内容 |
| --- | --- |
| `master` | 主线（默认开发分支） |
| `main` | 早期分支 |
| `feature` | 练习：新增猴子 |
| `mango` | 练习：新增芒果（与 panda 冲突并解决） |
| `panda` | 练习：新增熊猫 |
| `GIT2` | 练习：新增柚子 |

## 标签

`v1` → `v2` → `v3` → `v4`，对应水果清单的四个关键节点。

## 文件

- `fruits.txt` —— 练习用的清单
- `.gitignore` —— 排除规则（依赖、缓存、密钥）
- `.env.example` —— 配置示例（不含真实密钥）