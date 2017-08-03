本项目是Git学习记录，主要用于记录Git学习过程中笔者认为需要着重记忆的知识点。
资料参考：廖雪峰官方网站——Git教程

Git简介

Git是目前世界上最先进的分布式版本控制系统。所谓版本控制系统，是一种软体工程技巧，藉以在开发的过程中，确保由不同人所编辑的同一档案都得到更新。
版本控制透过文档控制记录程序各个模组的改动，并为每次改动编上序号。

Git是由Linux创始人Linus花费两周时间用C写就得版本控制系统，起初的目的是为了更好的管理Linux源码。后来迅速成为最流行的分布式版本控制系统，尤
其是2008年，GitHub网站上线之后，它为开源项目免费提供Git存储，无数开源项目开始迁移至GitHub。

作为一款分布式版本控制系统，Git与集中式版本控制系统SVN相比，分布式版本系统“去中心化”，即分布式没有“中央服务器”，每个人的电脑上都是一个完整
的版本库，这样在工作的时候就不要联网了，因为版本库就在自己的电脑上。既然每个人电脑上都有一个完整的版本库，那么多个人如何协作呢？比方说你在自
己电脑上改了文件A,你的同事也在他的电脑上改了文件A，这时，你们俩之间只需把各自的修改推送给对方，就可以互相看到对方的修改了。

和集中式版本控制系统相比，分布式版本控制系统的安全性要高很多，因为每个人电脑里都有完整的版本库，某一个人的电脑坏掉了不要紧，随便从其他人那里
复制一个就可以了。而集中式版本控制系统的中央服务器要是出了问题，所有人都没法干活了。






