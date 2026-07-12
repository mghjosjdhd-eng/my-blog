# 我的技术博客

个人技术博客，用 [Astro](https://astro.build) 构建，托管在 GitHub Pages。

## 技术栈

- **Astro 5** — 静态站点生成器
- **Markdown** — 文章格式
- **GitHub Actions** — 自动构建部署
- **GitHub Pages** — 免费托管

## 本地开发

```bash
npm install
npm run dev      # 开发服务器 → http://localhost:4321/my-blog
npm run build    # 构建到 dist/
npm run preview  # 预览构建产物
```

## 文章

所有文章放在 `src/content/posts/` 目录下，Markdown 格式。每篇文章需要包含 frontmatter：

```yaml
---
title: "文章标题"
date: 2026-07-01
description: "文章摘要"
tags:
  - 标签1
  - 标签2
---
```

## 部署

推送到 `main` 分支后，GitHub Actions 自动构建并部署到 GitHub Pages。
