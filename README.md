# Django 常用配置模板

## 第三方包

- djangorestframework
- django
- channels
- channels-redis
- celery
- redis
- daphne

## 如何使用

步骤如下

1. 创建你的工作环境。
2. 安装Django。
3. 运行命令
```
django-admin startproject --template https://github.com/HarryHEi/django-proj-template/archive/master.zip -e ini,conf,py proj
```

## 目录结构

+ conf: 包含nginx和supervisor常用配置
+ demo: 一个示例app
+ logs: 日志目录
+ proj: Django配置所在目录
