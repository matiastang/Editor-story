# pip安装

## pip简介

pip是常用的python包管理工具。

## 安装

1. 系统自带的python2.7的路径下安装

pip是python的包管理工具，在Python2.7的安装包中，easy_install.py是默认安装的，而pip需要我们手动安装。

终端输入如下安装：
```
$ sudo easy_install pip
```
2. python3的路径下安装

终端输入如下安装：
```
$ curl https://bootstrap.pypa.io/get-pip.py | python3
```

## 使用

* 查看版本
```
$ pip --version
```

* 查看安装的包
```
$ pip3 list
```

* 安装和更新pip
```
$ pip install --upgrade pip
```