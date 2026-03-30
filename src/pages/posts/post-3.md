---
layout: ../../layouts/MarkdownPostLayout.astro
title: '我的第三篇博客文章'
author: 'Elostirion'
description: "这篇文章会自己出现在列表中！"
image:
  url: "https://docs.astro.build/default-og-image.png"
  alt: "The word astro against an illustration of planets and stars."
pubDate: 2026-03-30
tags: ["astro", "successes"]
---
这篇文章也应该会与其他的博客文章一起显示，因为 `import.meta.glob()` 会返回一个包含所有文章的列表，以创建这个文章列表。