---
title: 多端同步hexo
date: 2023-07-23 21:50:56
tags: hexo
categories: 个人
---
 *又是一句:说来惭愧* 明明已经说过了,最终还是错了
# 开始：
windows:在一个空白的文件夹下
git clone git@(就是你博客hexo分支的ssh地址)
~~应该都新建了hexo 分支吧~~,这里就不再赘述
将.git 覆盖到你博客的.git文件上
进行 

```bush
git add .
git commit -m "备份hexo"
git pull origin hexo
```
应该就可以了

或者新建一个仓库
如果你只是source 文件有变动的话
建议只将source文件上传
# 最终结果
我现在的情况是
新建一个source仓库，然后将hexo的source文件夹的内容上传到仓库中，之后在其他平台，如手机 先git clone在进行手动将source文件夹里的内容更新
对对对，自己对自己的肯定