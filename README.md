# learning-sicp
学习 sicp

## 环境配置
### 1.安装 vscode 插件
安装 [magic racket](https://marketplace.visualstudio.com/items?itemName=evzen-wybitul.magic-racket) 插件
### 2.安装 racket
```sh
# windows
choco install racket -y 

# mac os
brew install racket

# linux ubuntu
sudo apt install racket
```
### 3.安装 language-server 
```sh
raco pkg install racket-langserver
```

## 开始开发
文件头添加下面的声明，以便用 scheme 语法
``` racket
#lang scheme
```
