---
#로고를 누르면 나타나는 메인 페이지
# Leave the homepage title empty to use the site title
title:
date: 2024-10-05
type: landing

sections:

  - block: features
    content:
      title: <span style="font-size:70%">안녕하세요. 전북대학교 컴퓨터 인공지능학부 이가은입니다.</span>
      text: <br><span style="font-size:125%">프론트에서 시작해 풀스택까지의 여정을 지켜봐주세요.</span> <br><br>
        {{% cta cta_link="./field/" cta_text="See Research Field →" %}}


  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Information</span>
        content: <span style="font-size:70%">이가은에 대해 더 자세히 알고싶다면?</span>
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: face-smile
          icon_pack: far
          text: <span style="font-size:60%">Click Me</span>
          text-color: '#000'
          url: contact

      - title: <span style="font-size:70%">안녕하세요.</span>
        content: <span style="font-size:70%">웹 개발자가 되고 싶은 이가은입니다.<span style="font-size:70%">
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Healthcare</span>
        content: <span style="font-size:70%">의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Mathematics</span>
        content: <span style="font-size:70%">AI와 관련된 수학 및 최적화 이론 연구</span>
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000


  - block: features
    id: features
    content:
      title: <span style="font-size:75%">Informaion</span>
      text: 이가은의 기본 정보<br><br><br><br>
      items:
        - name: 이름
          icon: user
          icon_pack: fas
          description: <span style="font-size:90%">이가은</span><br><br>
        - name: 생년월일
          icon: calendar-days
          icon_pack: fas
          description:  <span style="font-size:90%">2003.01.23</span><br><br>
        - name: 위치
          icon: location-dot
          icon_pack: fas
          description:  <span style="font-size:90%">전북대학교 공과대학 7호관</span><br><br>
        - name: 연락처
          icon: phone
          icon_pack: fas
          description:  <span style="font-size:90%">+82-5906-5988</span><br><br>
        - name: 이메일
          icon: envelope
          icon_pack: fas
          description:  <span style="font-size:90%">igaeun8@gmail.com</span><br><br>
        - name: 학력
          icon: pen
          icon_pack: fas
          description:  <span style="font-size:90%">전북대학교 컴퓨터 인공지능 학부</span><br><br>


  - block: collection
    content:
      id: section-1
      title: Project
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - project
    design:
      view: community/custom_card
      columns: '2'

  - block: collection
    content:
      title: Interests
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: field
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: collection
    content:
      title: Travel
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: 
          - travel_jejudo
          - travel_fukuoka
          - travel_danang
    design:
      view: showcase
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Join team →" %}}
    design:
      columns: '1'
---