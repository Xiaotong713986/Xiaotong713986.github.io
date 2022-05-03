# 修改网站内容
本文档将介绍如何通过增删改Markdown文件，改变网站内容。
## 修改Home内容
主页内容：/content/\_index.md

关于Recent News，可以通过以下命令新增信息：
> hugo new post/new-blog.md

通过以上命令后，将生成新的文件在/content/post/路径下

## 修改Group内容
主要内容： /content/group.md

主要数据路径：/content/person/

新增人员命令：
>hugo new person/2019-09-10-Tiantian-Zhang.md//(入学时间-张天天）

并在路径/static/person/下新增头像图片（TiantianZhang.jpg）

修改或删除人员数据则在主要数据路径下操作。

## 修改publications内容
主要内容：/content/pub/*.md

新增publications命令：
>hugo new pub/firstA.md

该markdown文件中的Pic为摘要图片，需要指定
在路径/static/firstA/下新增这篇publication的所有图片，并在markdown文件中引入


