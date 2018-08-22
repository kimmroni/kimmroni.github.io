---
title: 성음악기(CRAFTER)
description: 반응형 웹 구현, 페럴렉스 스크롤(parallax scroll) 디자인, 동영상 백그라운드 플러그인 적용, 제품등록 프로그램, 지역별 대리점 등록관리
categories:
 - 2015
tags: 기업, 반응형, 패럴렉스, 다국어
---
![Desktop Sidebar Preview](/assets/images/post/crafter.jpg)

> 프로젝트 기간 2015.04 ~ 2015.11

대한민국을 대표하는 기타 전문 브랜드 '성음악기(CRAFTER)' 의 리뉴얼 작업에 참여하였습니다.

트랜드에 맞는 패럴렉스 스크롤과 반응형 웹 구현에 최적화 되도록 작업하였으며 세계 각국에 대리점이 있어 사용자가 접근성이 쉽도록 영문사이트를 별도로 제작하였습니다.

다양한 기타의 장점을 부각하기 위해 디자인 컨텐츠들의 비주얼은 동영상으로 삽입되어 역동성을 더하고 풀사이즈 이미지들로 직관적이고 화려하게 다가가도록 제작하였습니다.

<!-- more -->

[Live Site](http://www.crafter.co.kr/)

## 프로젝트 참여도
디자이너 1 / 퍼블리셔1/ 개발자2 투입 되었으며 전체 참여율 디자인 100%
* 메인/서브:100%
* 컨텐츠:100%

## 메인시안
* PC

![Desktop Sidebar Preview](/assets/images/post/crafter_main.jpg)

* Mobile

![Mobile Preview](http://iissnan.com/nexus/next/mobile.png)


## Installation

Check whether you have `Ruby 2.1.0` or higher installed:

```sh
ruby --version
```

Install `Bundler`:

```sh
gem install bundler
```

Clone Jacman theme:

```sh
git clone https://github.com/Simpleyyt/jekyll-theme-next.git
cd jekyll-theme-next
```

Install Jekyll and other dependencies from the GitHub Pages gem:

```sh
bundle install
```

Run your Jekyll site locally:

```sh
bundle exec jekyll server
```

More Details：[Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)


## Features

### Multiple languages support, including: English / Russian / French / German / Simplified Chinese / Traditional Chinese.

Default language is English.

```yml
language: en
# language: zh-Hans
# language: fr-FR
# language: zh-hk
# language: zh-tw
# language: ru
# language: de
```

Set `language` field as following in site `_config.yml` to change to Chinese.

```yml
language: zh-Hans
```

### Comment support.

NexT has native support for `DuoShuo` and `Disqus` comment systems.

Add the following snippets to your `_config.yml`:

```yml
duoshuo:
  enable: true
  shortname: your-duoshuo-shortname
```

OR

```yml
disqus_shortname: your-disqus-shortname
```

### Social Media

NexT can automatically add links to your Social Media accounts:

```yml
social:
  GitHub: your-github-url
  Twitter: your-twitter-url
  Weibo: your-weibo-url
  DouBan: your-douban-url
  ZhiHu: your-zhihu-url
```

### Feed link.


> Show a feed link.

Set `rss` field in theme's `_config.yml`, as the following value:

1. `rss: false` will totally disable feed link.
2. `rss:  ` use sites' feed link. This is the default option.

    Follow the installation instruction in the plugin's README. After the configuration is done for this plugin, the feed link is ready too.

3. `rss: http://your-feed-url` set specific feed link.

### Up to 5 code highlight themes built-in.

NexT uses [Tomorrow Theme](https://github.com/chriskempson/tomorrow-theme) with 5 themes for you to choose from.
Next use `normal` by default. Have a preview about `normal` and `night`:

![Tomorrow Normal Preview](http://iissnan.com/nexus/next/tomorrow-normal.png)
![Tomorrow Night Preview](http://iissnan.com/nexus/next/tomorrow-night.png)

Head over to [Tomorrow Theme](https://github.com/chriskempson/tomorrow-theme) for more details.

## Configuration

NexT comes with few configurations.

```yml

# Menu configuration.
menu:
  home: /
  archives: /archives

# Favicon
favicon: /favicon.ico

# Avatar (put the image into next/source/images/)
# can be any image format supported by web browsers (JPEG,PNG,GIF,SVG,..)
avatar: /default_avatar.png

# Code highlight theme
# available: normal | night | night eighties | night blue | night bright
highlight_theme: normal

# Fancybox for image gallery
fancybox: true

# Specify the date when the site was setup
since: 2013

```

## Browser support

![Browser support](http://iissnan.com/nexus/next/browser-support.png)
