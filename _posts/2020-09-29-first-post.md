---
title: "minimal mistakes 테마를 이용해 github.io 블로그 구축하기"
categories: 
  - Blog
tags:
  - Blog
last_modified_at: 2020-10-01T13:11:30+09:00
toc: true
---

Jekyll 사용.

댓글은 Disqus

빌드는 Travis-CI

YFM에서 정의한 제목을 이중 괄호 구문으로 본문에 추가 가능.
이 글의 제목은 {{ page.title }}이고
마지막으로 수정된 시간은 {{ page.last_modified_at }}이다.

푸쉬전 로컬에서 최종확인 때 쓰는 명령어는

```ruby
#기본 디렉토리에서

bundle exec jekyll serve
```