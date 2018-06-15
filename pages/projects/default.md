---
title: Project Space

sitemap:
    changefreq: monthly
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 10
    pagination: true

feed:
    description: Projects
    limit: 10

pagination: true
---

