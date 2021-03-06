# BilibiliLink — 乾杯 - ( ゜ᴗ ゜)つロ

[![Build Status](https://travis-ci.org/GalAster/BilibiliLink.svg?branch=master)](https://travis-ci.org/GalAster/BilibiliLink)
[![Mathematica](https://img.shields.io/badge/Mathematica-%3E%3D11.3-brightgreen.svg)](https://www.wolfram.com/mathematica/)
[![Release Vision](https://img.shields.io/badge/release-v0.2.0-ff69b4.svg)](https://github.com/GalAster/BilibiliLink/releases)
[![Repo Size](https://img.shields.io/github/repo-size/GalAster/BilibiliLink.svg)](https://github.com/GalAster/BilibiliLink.git)

![](https://i.loli.net/2018/05/12/5af6f45da50ab.jpg)

## Introduce
![](https://i.loli.net/2018/05/13/5af7f64fa64ff.png)

BilibiliLink 提供了一系列获取B站数据的方法, 计划中的内容有, 文章下载, 文章评论下载, 画师画作下载, 评论下载, cosplay下载, 视频跟踪等等.

有什么想要的功能也可以在 github issue 中提出哦!

并非所有页面上的东西都能获得, 有些看着是文字, 其实是图片, 那就没法抓取了.

## Install
![](https://i.loli.net/2018/05/13/5af7f64fad2ca.png)
### 自动安装

版本号达到 v0.6.0 以后我会提交到部署服务器.

### 手动安装

打开目录:

```mma
SystemOpen[FileNameJoin@{$UserBaseDirectory, "Applications"}]
```

下载项目:

```bash
git clone git@github.com:GalAster/BilibiliLink.git --depth 1
```

#### Update

```bash
git pull
```

#### Uninstall

```bash
rm -rf BilibiliLink
```

## Show Time
![](https://i.loli.net/2018/05/13/5af7f64f7a266.png)

```mma
<< "BilibiliLink`
PhotosLeaderboard["help"]
link = PhotosLeaderboard["日榜"]
link["Markdown"]
```

## Todo List
![](https://i.loli.net/2018/05/13/5af7f64f9bc4c.png)

- 反正很多就是了

## Ideas
![](https://i.loli.net/2018/05/13/5af7f64f80b0f.png)
1. 任何创意欢迎 git pull request, 或联系知乎[酱紫君](https://www.zhihu.com/people/GalAster).
2. 任何的意见和建议, 提交 github issue 或者加QQ群1014125反馈.

|知乎主页|QQ群聊| 
|:-:|:-:|
|[<img src="https://raw.githubusercontent.com/GalAster/Deus/master/Resources/pic/Logo_Zhihu.png" alt="知乎链接" width = "100" align=center />](https://www.zhihu.com/people/GalAster)|[<img src="https://raw.githubusercontent.com/GalAster/Deus/master/Resources/pic/Logo_QQ.png" alt="QQ链接" width = "100" align=center />](https://jq.qq.com/?_wv=1027&k=5BqFya1)

- Copyrights of all pictures belong to **©bilibili.com**
- License of this project under **@Mozilla Public License Version 2.0**