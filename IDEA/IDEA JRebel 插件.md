# [TOC]
# IDEA JRebel 插件

## 前言
我们平时在项目开发过程中经常遇到在项目中只改动了其中一个很小的地方。重新调试的话需要重启整个服务， 这个步骤很耗费时间。

JRebel就是解决这个问题的，你只需要保存改完之后Java文件。无需重启整个服务就可以重新调试你修改过的代码

## 安装方式
可以去IDEA 插件市场前往下载

![-w514](http://it-learn.oss-cn-beijing.aliyuncs.com/2020/04/09/15863158778332.jpg)


## 激活方法
可以使用邮箱注册实现10天的免费试用。也可以通过网站注册激活

https://jrebel.qekang.com/
![-w539](http://it-learn.oss-cn-beijing.aliyuncs.com/2020/04/09/15863623230905.jpg)



## 插件设置
![-w981](http://it-learn.oss-cn-beijing.aliyuncs.com/2020/04/09/15863521583133.jpg)

![-w1053](http://it-learn.oss-cn-beijing.aliyuncs.com/2020/04/09/15863623674785.jpg)

## 插件使用
需要我们在服务中勾选使用Jrebel，使得我们的服务支持JRebel热部署
![-w984](http://it-learn.oss-cn-beijing.aliyuncs.com/2020/04/09/15863522300753.jpg)


## 添加到gitignore

这里需要注意的是只有unversioned 的文件才可以加入到.gitignore
![-w2200](http://it-learn.oss-cn-beijing.aliyuncs.com/2020/04/09/15863617976999.jpg)

>You must have added these files to the repository already... .gitignore is not used when selecting files to commit, it's used for adding only: files listed there are not suggested to be added. But, once they are added, they appear in Local Changes

详见
https://intellij-support.jetbrains.com/hc/en-us/community/posts/115000001824-I-have-idea-in-gitignore-but-it-is-still-in-local-changes
## 参考资料
https://www.jianshu.com/p/d4a87a5f307c