---
title: "如何使用 Hugo 写文章"
date: 2025-12-24T21:30:00+08:00
tags: ["Hugo", "教程", "写作"]
categories: ["技术", "博客"]
draft: false
---

# 如何使用 Hugo 写文章

Hugo 是一个快速的静态网站生成器，非常适合搭建博客。本文将介绍如何使用 Hugo 写文章和分类。

## 创建新文章

要创建新文章，使用以下命令：

```bash
hugo new posts/文章标题.md
```

## Front Matter 元数据

每篇文章顶部都有 Front Matter 部分，用来定义文章的元数据：

```yaml
---
title: "文章标题"
date: 2025-12-24T21:30:00+08:00
tags: ["标签1", "标签2"]
categories: ["分类1", "分类2"]
draft: false  # 设为 true 暂不发布
---
```

## 分类与标签

- **Categories（分类）**：用于组织内容的层级结构
- **Tags（标签）**：用于标记文章的关键字

## Markdown 语法

在 Front Matter 下方使用 Markdown 语法编写内容：

```markdown
# 标题

这里是文章内容...

## 小节标题

更多内容...
```