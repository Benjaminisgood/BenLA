<p align="center">
<h1 align="center"> <img src="./imgs/icon/ai.png" width="30" /> 科学计算+数学+物理+化学+机器学习+人工智能的n合一学习笔记</h1>

本人化学专业，半路出家学习将计算机与AI融入日常科研。
本项目用 jupyter lab 作为自己的学习记录，如果能帮到其他人那就太好了。
本项目不断发展中，旨在用编程的方法学习数学、科学计算与机器学习。

---

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
git log --oneline    # 查看提交历史简要
git diff             # 查看更改详情
```

---

## ⚖️ 处理本地与远程分支分叉（diverged）

如果你看到提示：

```
Your branch and 'origin/main' have diverged
```

推荐使用如下命令合并：

```bash
git pull --rebase origin main  # 拉取并合并远程的提交（推荐方式）
# 解决冲突（如有）后：
git add .
git rebase --continue

git push  # 推送已合并的提交
```

如你确定远程无用、只保留本地内容（危险）：

```bash
git push --force
```

---

## 📆 后续工作流推荐

日常更新：

```bash
git status               # 查看状态
git add .                # 添加修改
git commit -m "描述信息"  # 提交
git pull --rebase origin main  # 拉取远程改动
# 解决冲突后：
git push                # 推送更新
```

查看日志、版本回溯：

```bash
git log --oneline       # 简洁日志
```

保存临时工作：

```bash
git stash               # 暂存未完成更改
git stash pop           # 恢复更改
```

此流程适合个人项目快速迭代，后续如有多人协作建议加入分支管理与 PR 流程。
  

git add . 
git commit -m "描述信息"
git push    