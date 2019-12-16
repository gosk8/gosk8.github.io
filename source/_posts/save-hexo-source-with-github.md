---
title: 使用Github同步Hexo源码
date: 2019-12-12 10:33:25
tags:
---


<!--more-->

由于Github Pages是指定使用master分支的，所以同步源码的原理就是在项目下新建一个分支单独保存源码。

# 新建源码分支

- 基于master分支新建保存源码的分支，步骤略

- 添加.gitignore，内容如下:

```text
.DS_Store
Thumbs.db
db.json
*.log
node_modules/
public/
.deploy*/
```

# 设置Hexo deploy分支

Hexo默认的deploy分支就是master，这里可以不用去动

# Enjoy it.