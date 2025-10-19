# git 配置

1.下载git bash

2.输入代码

git --version           检验是否下载成功

git config --global user.name "2502caishijie"            姓名

git config --global user.email "841757401@qq.com"            邮箱

git config --list             查看是否成功

# ssh密钥

在git bash里输入代码

git clone https://github.com/sDNu-Robotics-Lab/2025-2026-2502caishijie

ls -al ~/.ssh

ssh-keygen -t ed25519 -C "841757401@qq.com"

cat ~/.ssh/id_ed25519.pub

ssh -T git@github.com

输出

Hi 2502caishiiie! You've successfully authenticated, but GitHub does not provideshell access.

# learn git

* 拥有push权限

1.创建仓库

2.clone到本地，复制url

git clone +url

git status

git add .

git commit -m "test"

git push

* 不拥有push权限

fork仓库

git checkout -b "csj"

切换分支 创建

git add .

git commit -m "Second"

git push

复制

# 学习心得

通过本次学习，我掌握了Git的基本使用方法，理解了版本控制的重要性。学会了如何配置Git环境、使用基础指令管理代码，以及如何通过GitHub进行团队协作和作业提交。





