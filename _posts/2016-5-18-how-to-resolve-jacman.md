---
layout: post
title: 使用 Jacman 主题  常见错误
tags:
- Jacman 主题 使用
- Jekyll
categories: Jekyll
---

**在使用 Jacman 主题 ,错误1：当运行jekyll --server 提示**

![My jekyll_server screenshot]({{ site.url }}/assets/2016.5.18/jekyll_server.jpg)

 解决方案：
 
 (1) 你需要将Gemfile source 'https://rubygems.org'->source 'http://rubygems.org' [链接](http://stackoverflow.com/questions/27484567/make-sure-that-gem-install-succeeds-before-bundling) 这样在你运行下面命令，就不会一直报 "Make sure that 'gem install ~ ' succeeds before bundling"

 (2) sudo gem install bundler -v 
  
 (3) bundle install -V
 
 (4) bundle exec jekyll serve  
 

     
 