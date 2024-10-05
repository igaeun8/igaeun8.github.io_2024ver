---
#로고를 누르면 나타나는 메인 페이지
# Leave the homepage title empty to use the site title
title:
date: 2024-09-30
type: landing

sections:
  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">안녕하세요.웹 개발자가 되고 싶은 이가은입니다. 프론트에서 시작해 풀스택까지의 여정을 지켜봐주세요.</span>

  - block: slider
    content:
      slides:
      - title: AI
        content: 'Just opened last month!'
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: Medical AI
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Development
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Mathematics
        content: 'Just opened last month!'
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000