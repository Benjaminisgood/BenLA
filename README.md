<p align="center">
<h1 align="center"> <img src="./imgs/icon/ai.png" width="30" /> 科学计算+数学+物理+化学+机器学习+人工智能的n合一学习笔记</h1>

本人化学专业，半路出家学习将计算机与AI融入日常科研。
本项目用jupyter lab 作为自己的学习记录，如果能帮到其他人那就太好了。
本项目不断发展中，旨在用编程的方法学习数学、科学计算与机器学习。

## 🚀 Git 使用指南

### ✅ 新项目上传 GitHub（首次推送）

```bash
git init
git add .
git commit -m "Initial commit"

git remote add origin https://github.com/用户名/仓库名.git
git branch -M main
git push -u origin main
```

### ✅ 如果远程仓库已存在文件（如 README）

```bash
git pull --rebase origin main  # 拉取并合并远程内容（推荐）
git push -u origin main        # 推送同步
```

### ⚠️ 若确认远程内容可被覆盖，强制推送：

```bash
git push -u origin main --force
```

### 🌿 常用 Git 命令补充

```bash
git status           # 查看当前状态
git add .            # 添加所有更改
git commit -m "信息" # 提交更改
git stash            # 暂存当前更改（临时保存）
git stash pop        # 恢复暂存的更改
```
