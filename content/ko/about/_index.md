---
#about을 누르면 나타나는 페이지
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">안녕하세요. 웹 개발자가 되고 싶은 이가은 입니다. 프론트에서 시작해 풀스택까지의 여정을 지켜봐주세요.</span></br>


  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">About Me</span>
        content: <span style="font-size:90%">컴퓨터와 친해지고 싶은<span style="font-size:90%">
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Interests</span>
        content: <span style="font-size:90%">관심 분야가 많은 </span>
        align: center
        background:
          image:
            filename: data_science.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Travel</span>
        content: <span style="font-size:90%">여행을 좋아하는</span>
        align: center
        background:
          image:
            filename: iot.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Front-end</span>
        content: <span style="font-size:90%">프론트 엔드 개발 지망 학부생</span>
        align: center
        background:
          image:
            filename: cloud_computing.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'


      - title: <span style="font-size:90%">이가은</span>
        content: <span style="font-size:90%">이가은에 대해 더 알아보기</span>
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Click me</span>
          text-color: '#000'
          url: contact

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  # - block: hero
  #   content:
  #     title: |
  #       <span style="font-size:75%">Medical AI & Computational Science (MACS) Lab</span>
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
        
  #       <span style="font-size:75%">전북대학교 의료 AI 및 계산 수학 연구실 (MACS Lab) 홈페이지에 오신 것을 환영합니다. MACS에서는 의료, 항공, 국방 분야에 AI 및 딥러닝을 활용한 연구를 수행하고 있으며, 의료 수학 및 AI 기반 연구도 함께 수행하고 있습니다. 뿐만 아니라, 풀스택 개발 및 AI를 활용한 어플리케이션 개발 등 Development & Deploy하는 실용적인 분야에도 집중하고 있습니다.</span>
  
---