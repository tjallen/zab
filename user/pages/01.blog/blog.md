---
title: Home
blog_url: blog
body_classes: header-image fullwidth

sitemap:
    changefreq: monthly
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true

feed:
    description: Zabby Allen: The girl with all the craft supplies
    limit: 10

pagination: true
---
