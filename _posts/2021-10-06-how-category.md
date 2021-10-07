---
date: 2021-10-06
title: "[GitBlog] 카테고리 세팅하기"
excerpt: "우측 상단 Quick-Start-Guide를 나만의 메뉴로 바꿔보자!"
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
```
# main links
main:
  - title: "About"      # ex)Quick-Start-Guide 
    url: /about/        # About 특정 링크로 연결. 아래에서 더 다뤄보겠다.
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

> _data 폴더 > navigation.yml 파일에서 url을  
> _page 폴더 > .md 파일에서 permalink 와 맞춰야지 작동하는 것 같다.