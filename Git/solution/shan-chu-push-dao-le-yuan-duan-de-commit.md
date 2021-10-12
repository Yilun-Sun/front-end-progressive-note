---
description: 啊呀！不小心提交了不该提交的 commit！怎么办！
---

# 删除 push 到了远端的 commit

先在 local 把错误的 commit 抹去

命令：`git reset --hard {COMMIT_HASH}` 也可以用 `--soft` 保留修改

{% hint style="warning" %}
这里的 `{COMMIT_HASH}` 是错误提交了的 commit 的上一个 commit 的哈希值
{% endhint %}

之后需要覆写远程服务器

命令：`git push origin HEAD:master --force` 

记得加 `--force`，不加的话服务器会拒绝，无法提交

查看远端的记录，发现 commit 历史已经变成了想要的模样，似乎什么都没发生过
