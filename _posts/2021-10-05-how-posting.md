---
date: 2021-10-05
title: "[GitBlog] 블로그 포스팅 방법"
excerpt: "포스팅을 연습해보자!"
categories: 
    - Blog
tags: 
    - [Blog, Git, Github, jekyll]
toc: true
toc_sticky: true
last_modified_at: 2021-10-05 
---

# 1. Markdown을 지원하는 에디터를 실행한다.
---
나는 Visual Studio Code로 진행했다. 에디터를 실행하고 **깃허브아이디.github.io** 이름의 폴더를 열어주었다.

# 2. _posts 폴더를 생성한다.
---
모든 블로그 게시글은 이 폴더 안에 생성할 것이다.
깃블로그 테마별로 다른 지는 모르겠지만, 폴더가 이미 있다면 폴더 안에 yyyy-mm-dd-title.md 형식의 파일을 만든다.   
ex) 2021-10-05-first-post.md

# 3. 머릿말(Front-Matter)을 상단에 작성한다.
---
내용을 작성하기 전에 이 포스트의 정보를 머릿말로 적어주는 것이다.
~~~
---
date: 2021-10-05
title: "[GitBlog] 신나는 첫 포스팅"
excerpt: "md 파일에 마크다운 문법으로 작성하여 GitBlog 첫 포스팅을 해보자!"
categories: 
    - Blog
tags: 
    - [Blog, Git, Github, jekyll]
toc: true
toc_sticky: true
last_modified_at: 2021-10-05 
---
~~~
**date**: 작성날짜   
**title**: 게시글 제목 입력하지 않으면 md파일의 title부분이 게시글의 제목이 된다. ``` ex) First post```   
**excerpt**: 게시판에서 보여지는 게시글의 소개(요약)으로 들어간다.   
**toc**: Table of Contents 포스트의 헤더들만 보여주는 목차를 사용할 것인지에 대한 여부. ```true```로 해주면 포스트의 목차가 보이게 된다.   
**toc_sticky**: ```true```로 해주면 목차가 스크롤을 따라 움직이게 된다.   

# 4. 이제 내용을 적어보자!
---
```---``` 로 머릿말을 끝냈다면 그 아래에 **Markdown** 문법으로 내용을 작성해보자.
마크다운 문법은 인터넷에 검색하면 친절하게 나와있다.

# P.S
깃블로그 게시글 작성을 위해 구글링하며 어찌저찌 포스팅 하는 방법으로 첫 게시글을 작성하게 되었다. 하나씩 알아가는 것이 재미가 있다. 더 열심히 해야겠다.
**첫 기록 끝**