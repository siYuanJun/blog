---
title: Git 高级
tags: git
categories: git
abbrlink: '8fc9'
---


# Git 高级

- git https 可以不总输入密码
  sudo git config --global credential.helper store

- 删除git帐号缓存
  rm ~/.git-credentials

- Git rebasing，多半是由于提交冲突所致，

- 如果想要放弃当前rebase操作，用
   git rebase --abort

- 如果冲突已经解决，先add冲突文件，之后
   git rebase --continue

- 大文件处理方法
  https://blog.csdn.net/xiaoxiong_web/article/details/127312231


