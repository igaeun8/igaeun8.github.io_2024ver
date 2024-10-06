# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">Hello. I am Lee Gaeun, aspiring to become a web developer. I started with front-end and hope you follow my journey towards full-stack development.</span></br>


  - block: slider
    content:
      slides:
      - title: <span style="font-size:90%">About Me</span>
        content: <span style="font-size:90%">I want to get closer to computers<span style="font-size:90%">
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Interests</span>
        content: <span style="font-size:90%">I have many areas of interest</span>
        align: center
        background:
          image:
            filename: data_science.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Travel</span>
        content: <span style="font-size:90%">I love to travel</span>
        align: center
        background:
          image:
            filename: fukuoka.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Front-end</span>
        content: <span style="font-size:90%">An undergraduate aspiring to become a front-end developer</span>
        align: center
        background:
          image:
            filename: coding.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'


      - title: <span style="font-size:90%">Lee Gaeun</span>
        content: <span style="font-size:90%">Learn more about Lee Gaeun</span>
        align: center
        background:
          image:
            filename: avatar.jpg
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
