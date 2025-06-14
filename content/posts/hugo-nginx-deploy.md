---
title: "Hugo + Nginx 博客部署全流程"
date: 2024-06-15
description: "手把手教你用 Hugo 和 Nginx 搭建个人博客，并实现 HTTPS"
tags: ["Hugo", "Nginx", "建站", "运维"]
categories: ["技术干货"]
---

# Hugo + Nginx 博客部署全流程

本文详细介绍如何用 Hugo 生成静态博客，并用 Nginx 部署到云服务器，实现 HTTPS 访问。适合新手和有一定基础的开发者。

## 步骤一：Hugo 本地生成静态页面

1. 安装 Hugo
2. 创建新站点
3. 选择主题
4. 写文章
5. 生成静态文件

## 步骤二：Nginx 配置静态站点

1. 安装 Nginx
2. 配置 server 块，指向 Hugo 的 public 目录
3. 检查权限和访问效果

## 步骤三：申请免费 SSL 证书

1. 安装 certbot
2. 用 certbot 自动为域名申请证书
3. 配置 HTTPS 跳转

## 常见问题与排查

- 403 Forbidden 如何解决？
- Hugo 主题美化技巧
- Nginx 配置优化建议

> 欢迎留言交流你的部署经验！ 