# Concise

[中文说明](/README_ZH.md)

Concise is the theme I currently use for [Hexo](http://hexo.io/). It is based on [Light](https://github.com/hexojs/hexo-theme-light) and [Pacman](https://github.com/A-limon/pacman). See my blog as a [Demo](http://opiece.me/).

## Install

Execute the following command and Modify `theme` setting in blog folder
` _config.yml` to `concise`.

```
git clone https://github.com/huangjunhui/concise.git themes/concise
```

## Update

Execute the following command .

```
cd themes/concise
git pull origin master
```

##Configuration

Modify settings in  `/themes/concise/_config.yml`.


## Features

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar.The category,tag,rss,search,tagcloud,links,weibo are supported.
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **twitter** - Twitter widget config
  - **username** - Twitter username
  - **show_replies** - Enable displaying replies
  - **tweet_count** - Tweets display in widget
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)
- **author**  
 Author imformation, used to show your social network links on the bottom right. Including github,  twitter, facebook, linkedin, google+, weibo, tsina.
- **Image**  
 Images about favicon, site logo, author image. 

### Gallery Post

![](http://i.minus.com/ibp6Hbytwgof9y.jpg)

```
---
layout: photo
title: Gallery Post
photos:
- http://i.minus.com/ibobbTlfxZgITW.jpg
- http://i.minus.com/iedpg90Y0exFS.jpg
---
```

### Link Post

![](http://i.minus.com/i7hBbGqh14EWo.png)

```
---
layout: link
title: Link Post
link: http://www.google.com/
---
```

### Tweet Widget

![](http://i.minus.com/iMC8EyF9y0Y3y.PNG)

### Fancybox

![](http://i.minus.com/iHv7h7rZNqHvo.PNG)

[Hexo]: http://hexo.io/
[AddThis]: https://www.addthis.com
[Fancybox]: http://fancyapps.com/fancybox/