# Git 练习仓库

第一个本地 Git 仓库，用来练 `add` / `commit` / `push`。

## 一句话记住三者关系

- **Git**：管「记下每一次改动」，装在你电脑上，断网也能用。
- **GitHub**：管「把记录存到云上并让人看见」。
- **绑定**：管「证明你是你」，只有 push / 读写私有仓库时才需要。

## 常用命令

| 命令 | 作用 |
| --- | --- |
| `git status` | 看当前改了什么 |
| `git add .` | 把改动放进暂存区 |
| `git commit -m "说明"` | 拍一张快照 |
| `git log --oneline` | 看历史快照 |
| `git remote -v` | 看云端地址 |
| `git push` | 推到 GitHub |
| `git pull` | 从 GitHub 拉回来 |

## 终端小抄（UCRT64 / Git Bash）

- 复制：鼠标左键拖选，松手即复制
- 粘贴：鼠标右键，或 `Shift + Insert`
- `Ctrl + C` 是中断程序，不是复制；`Ctrl + S` 会冻结屏幕，用 `Ctrl + Q` 解冻

## SSH 地址格式

```
git@github.com:vvv-sour/仓库名.git
```

冒号后面必须是「用户名 / 仓库名」，只写用户名会报 `Repository not found`。
