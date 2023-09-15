---
title: 本地git用户名和邮箱配置
date: 2023-09-13 09:37:15
tags: Git
categories: Git
excerpt: 本地git配置
---

{% asset_img 84806f2bccb0466e82280b7fc48e2cd8.jpg This is an example image %}

要使用git，需要配置用户名和邮箱<span style="color:red;">（邮箱可以不配置）</span>。  

## 检查本地git配置

``` bash
# 查看user.name
git config user.name
# 查看user.mail
git config user.email
```
如果上述的用户名和邮箱都为空，那么就需要进行配置了。  

## 设置本地git配置

- git config --global `user.name` ${username}
- git config --global `user.email` ${usermail}

``` bash
# 这里配置用户名是test
git config --global user.name test
# 这里配置邮箱是test@mail.com
git config --global user.email test@mail.com
```

