---
title: "搭建个人博客之旅：Hugo + PaperMod 主题"
date: 2025-01-25T15:30:00+08:00
draft: false
tags: ["Hugo", "教程"]
categories: ["技术笔记"]
author: "Ruby"
---

## 为什么选择 Hugo？

Hugo 是一个用 Go 语言编写的静态网站生成器，以其快速的构建速度和简单的配置而闻名。今天，我将分享我使用 Hugo 搭建个人博客的经验。

### 主要优势

1. 超快的构建速度
2. 简单的配置过程
3. 丰富的主题选择
4. Markdown 写作支持

## 搭建过程

### 1. 安装 Hugo

```bash
# macOS
brew install hugo

# Windows
choco install hugo
```

### 2. 创建新站点

```bash
hugo new site myblog
cd myblog
```

### 3. 安装主题

我选择了简洁优雅的 PaperMod 主题：

```bash
git clone https://github.com/adityatelange/hugo-PaperMod.git themes/hugo-PaperMod
```

## 写作体验

使用 Markdown 写作非常舒适，支持代码高亮：

```python
def hello_hugo():
    print("Welcome to my blog!")
    return "Happy Blogging!"
```

## 后续计划

- [ ] 添加评论系统
- [ ] 优化 SEO
- [ ] 添加自定义样式
- [ ] 集成统计功能

---

这是我的第一篇博客，后续会持续分享更多技术内容，敬请关注！
