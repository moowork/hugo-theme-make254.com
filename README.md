

# Features

* Google Analytics
* Disqus
* Share Buttons(fb, twitter, google+, pocket)
* Eye-catching Image
* MicroData
* Readable text(Customized Vertical Rhythm).

# Installation

[hugoThemes#Installing Themes](https://github.com/spf13/hugoThemes#installing-themes).

# Configuration

**config.yaml**

``` toml
baseurl = "http://hugo.spf13.com/"
title = "Hugo Themes"
copyright = "Copyright (c) 2008 - 2014, Steve Francia; all rights reserved."
canonifyurls = true
paginate = 3

[params]
  disqusShortname = "your disqus id." # optional
```

**example post**

``` toml
+++
title = "Getting Started with Hugo"

author = "Mr. author"
authorLink = "http://moowork.com/erik"
description = ""
tags = [
    "go",
    "golang",
    "hugo",
    "development",
]
date = "2014-04-02"
categories = [
    "Development",
    "golang",
]

image = "image.jpg" # optional
toc = false # optional, When set to FALSE this parameter, table of contents not appears in only this article.
+++

Contents here
```


Based on the [Robust](https://github.com/dim0627/hugo_theme_robust) hugo theme by [Daisuke Tsuji](http://yet.unresolved.xyz/)

Made by [Erik Kaareng-Sunde/moowork](http://moowork.com)