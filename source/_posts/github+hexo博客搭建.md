---
title: 如何搭建github博客
date: 2019-04-18 10:23:24
tags: 
	- other
---
参考[小茗同学的博客园](https://www.cnblogs.com/liuxianan/p/build-blog-website-by-hexo-github.html)。感谢该博客！下面是给自己备份的一些技术细节，写的比较简单，仅作为本人参考，大家遇到问题，可以参考[小茗同学的博客园](https://www.cnblogs.com/liuxianan/p/build-blog-website-by-hexo-github.html)。当然，有问题欢迎大家联系我。


## 关于安装环境配置

1. 注册github账户
2. 安装git
3. 安装TortoiseGit
4. 安装nodejs

## 注意事项

1. github创建自己的仓库，仓库命名：[你的git名字].github.io
2. 配置SSH key，本地和github通讯必须

## 其它
1. 博客主题没有采用github pages提供的模板，而是采用hexo进行管理，主题选择了[litten的yilia](https://github.com/litten/hexo-theme-yilia)。感谢litten。
2. 如果部署阶段出现如下错误：‘ERROR Deployer not found: git’，请安装npm install hexo-deployer-git --save