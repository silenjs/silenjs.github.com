---
layout: post
title: 'nodejs'
date: 2015-01-10 12:47
categories: Mac
---
### Mac 安装

brew *homebrew*    
nvm->nodejs ->snodejs version


brew install nvm

- `source $(brew --prefix nvm)/nvm.sh` 添加到环境变量
- `nvm -ls remote` 查看远程版本 
- `nvm install (version)`


### Linux 安装

*源码安装*   

- python -V >2.6.6
- wget (nodejs官网源码下载地址)
- tar zxvf node.tar.gz(解压)
- cd node
- ./configure
- make
- make install
- done!