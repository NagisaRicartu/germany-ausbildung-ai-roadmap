# Day 1 Learning Review

日期：2026.7.14

## 今天完成了什么

- 创建 GitHub 账号
- 创建公开仓库 germany-ausbildung-ai-roadmap
- 配置本地 Git 仓库
- 创建并推送 README.md
- 创建并推送 versions.md
- 学习 git add、git commit 和 git push 的区别
- 解决 Git 代理连接失败的问题

## 今天理解的概念

### Git

Git 是安装在本地电脑上的版本控制工具，用于记录项目文件的变化历史。

### GitHub

GitHub 是托管 Git 仓库的在线平台，可以用于远程备份、展示项目和团队协作。

### git add

`git add` 把指定文件的改动放入暂存区，决定下一次 commit 包含什么。

### git commit

`git commit` 在本地创建一次带有说明的项目快照。

### git push

`git push` 把本地已经创建的 commit 上传到 GitHub。

## 今天遇到的问题

### 问题 1：GitHub 设备登录没有手机验证码

原因：设备验证码显示在运行 `gh auth login` 的终端中，而不是手机中。

解决方法：从终端复制一次性设备码，并在 GitHub 设备授权页面输入。

### 问题 2：git push 无法连接

报错中出现：

```text
Failed to connect to 127.0.0.1 port 11671