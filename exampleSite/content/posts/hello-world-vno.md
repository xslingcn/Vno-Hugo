---
layout: post
tags: ["Say Hi", "Vno"]
title: "Hello World Vno"
date: 2021-07-19T07:28:27+08:00
math: false
draft: false
---
#### What's this

[Vno Hugo](https://github.com/xslingcn/vno-hugo) is a theme for [Hugo](https://gohugo.io). It is a port of [onevcat](https://onevcat.com)'s [Vno Jekyll](https://github.com/onevcat/vno-jekyll), which is originally developed from [Dale Anthony's Uno](https://github.com/daleanthony/uno).

#### Usage
Inside the folder of your Hugo site run:
```bash
$ git submodule add https://github.com/xslingcn/vno-hugo.git themes/vno-hugo
```
Copy everything in the `exampleSite` folder to the root of your hugo site, then run `hugo serve`. Your site with `Vno Hugo` enabled should be accessible in http://localhost:1313/.

For more information about Hugo, please visit [Hugo's site](https://gohugo.io).

#### Configuration

All configuration could be done in `config.yml`. Everything in the config file should be self-explanatory.

If you want to enable MathJax support, set `math` param in the front matter to `true`.

#### Background image and avatar

You could replace the background and avatar image in `static/images` folder to change them.

