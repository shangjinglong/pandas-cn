# 翻译贡献指南

想要参与翻译的小伙伴，请注意。

参与翻译的提前技能有：[Git](https://zh.wikipedia.org/zh-hans/Git)、[Markdown](https://zh.wikipedia.org/wiki/Markdown)、[命令行操作](https://zh.wikipedia.org/wiki/%E5%91%BD%E4%BB%A4%E8%A1%8C)、[英语](https://zh.wikipedia.org/wiki/%E8%8B%B1%E8%AF%AD)（Google翻译也可）

## Git教程

这里推荐一个很不错的开源Git教程：[https://github.com/geeeeeeeeek/git-recipes](https://github.com/geeeeeeeeek/git-recipes)

## Markdown教程

这里推荐一个不错的Markdown教程：[https://www.appinn.com/markdown/](https://www.appinn.com/markdown/)

在线编辑器推荐使用这个：[https://pandao.github.io/editor.md/](https://pandao.github.io/editor.md/)

## 文档如何在本地跑起来？

Pandas 中文文档的最新版本使用的是 [VuePress](https://v1.vuepress.vuejs.org/zh/) 文档生成工具来驱动的。

如果你想让文档在本地运行调试，你首先需要安装[Nodejs](http://nodejs.cn/)在你的电脑上，非Windows操作系统推荐使用[nvm](https://github.com/nvm-sh/nvm/blob/master/README.md)来安装[Nodejs](http://nodejs.cn/)，Windows操作系统的小伙伴可以直接下载最新版本的Nodejs的[Windows 安装包](http://nodejs.cn/download/)。

## 命令教程

请先打开命令行或者终端工具，然后切换到文档所在的目录，然后运行以下功能命令。

### 安装文档工具的依赖

这一步是必须的！

``` bash
$ npm install
```

### 运行本地环境

查看翻译效果，可以运行这个命令。

``` bash
$ npm run dev
```

### 生成静态html文件

``` bash
$ npm run build
```