---
layout:     post
title:      Django虚拟环境搭建
category:   article
description: Django虚拟环境搭建
---


# 搭建Django虚拟运行环境

在Python工作环境中，经常会遇到使用相同库不同版本的情况，为了兼容，我们可以使用虚拟环境

安装

```
#/usr/local/python/bin/pip install virtualenv
```
创建虚拟环境
```
#/usr/local/python/bin/virtualenv /usr/local/django1811
```
切换到虚拟环境
```
#source /usr/local/django1811/bin/activate
```
安装python库
```
(django1811) [root@jyw-w-salt02 testm2m]#

  pip install django==1.8.11
  pip install django_grappelli==2.7.3
```
退出虚拟环境
```
#deactivate
```
运行
```
#/usr/local/django1811/bin/python manage.py  runserver
```
