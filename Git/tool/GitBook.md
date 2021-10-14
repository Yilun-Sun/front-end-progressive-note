---
description: 对，就是用这玩意写的
cover: >-
  https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FNkEGS7hzeqa35sMXQZ4X%2Fuploads%2Fgit-blob-0d91e3d537f828d1fc7dfd2670840578d0f19cba%2FSpace.png?alt=media
coverY: 257.5953079178886
---

# 📘 GitBook

{% hint style="warning" %}
不要打包！不要打包！不要打包！
{% endhint %}

## 是个什么玩意

> GitBook is a modern documentation platform where teams can document everything from products to internal knowledge-bases and APIs.

其实就是个好看点的 Markdown

## 安装

准备好 node 然后全局安装 gitbook-cli\
`npm install gitbook-cli -g`

新建项目文件夹，进入文件夹在终端运行\
`gitbook init`

如果出现

```
info: create README.md
info: create SUMMARY.md
info: initialization is finished
```

就成功了

{% hint style="info" %}
如果有报错的话可能就是 node 版本问题 可以安装 nvm 去切换 node 版本或者直接安装最新/对应的版本，之后重新执行 `git init`
{% endhint %}

## Sync GitHub 仓库

GitBook 可以同步所有者的某个 GitHub 仓库中的内容。链接好之后，每次仓库中的变动都可以触发 GitBook 的同步，把新的内容在 GitBook 中显现出来。

GitBook 在线平台的提交修改和 Merge 的对象都是你的远程 repo，还想在本地继续修改的话，就要注意在本地的 repo 及时 pull 下来远程的更新。不然本地和远程就错开了。

所以你可以有多种撰写文档或者文章的工作流：

* local repo -> push to online repo -> sync in GitBook -> <mark style="color:green;">Done!</mark>
* edit in online GitBook dashboard -> <mark style="color:green;">Done!</mark>
* edit in online GitBook dashboard -> merge changes to online repo -> pull in local repo -> <mark style="color:green;">Done!</mark>
