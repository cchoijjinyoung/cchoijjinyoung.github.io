---
date: 2021-10-06
title: "[GitBlog] 카테고리 세팅하기"
excerpt: "우측 상단 Quick-Start-Guide를 나만의 카테고리로 바꿔보자!"
categories: 
    - Blog
tags: 
    - [Blog, Git, Github, jekyll]
toc: true
toc_sticky: true
last_modified_at: 2021-10-06 
---

# 1. navigation.yml 수정.
- github.io 폴더 > _data 폴더  > navigation.yml
```yml
# main links
main:
  - title: "About"      # ex)Quick-Start-Guide 
    url: /about/        # About 특정 링크로 연결.
  - title: "Category"
    url: /categories/
  - title: "Tags"
    url: /tags/
```

# 2. Page 수정.
- github.io 폴더 > _pages 폴더 > about.md(*예시 입니다.)
```
---
title: "About"
layout: about
permalink: /about/
toc: true
toc.sticky: true
author_profile: true
---
 # 여기서부터는 'About' page에 맞게 자기소개 적는 곳.
```