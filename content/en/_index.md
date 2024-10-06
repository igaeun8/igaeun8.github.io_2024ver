---
# Main page that appears when clicking the logo
# Leave the homepage title empty to use the site title
title:
date: 2024-10-05
type: landing

sections:

  - block: features
    content:
      title: <br><span style="font-size:125%">Hello, I'm Gaeun Lee, aspiring to become a web developer.</span>
      text: <br><span style="font-size:100%">Watch my journey from frontend to full stack development.</span>

  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">Information</span>
        content: <span style="font-size:70%">Want to know more about I Gaeun?</span>
        align: center
        background:
          image:
            filename: web_develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
          color: '#000'
          css_class: "image-overlay"  # Add the CSS class for text overlay
        link:
          icon: face-smile
          icon_pack: far
          text: <span style="font-size:60%">Click Me</span>
          text-color: '#000'
          url: contact
      - title: <span style="font-size:90%">About Me</span>
        content: <span style="font-size:90%">Wants to get closer to computers</span>
        align: center
        background:
          image:
            filename: human_computer_interaction.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Interests</span>
        content: <span style="font-size:90%">Interested in various fields</span>
        align: center
        background:
          image:
            filename: data_science.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Travel</span>
        content: <span style="font-size:90%">Loves to travel</span>
        align: center
        background:
          image:
            filename: fukuoka.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
      - title: <span style="font-size:90%">Front-end</span>
        content: <span style="font-size:90%">Aspiring front-end development student</span>
        align: center
        background:
          image:
            filename: coding.jpg
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
      title: <span style="font-size:75%">Information</span>
      text: Basic information about I Gaeun<br><br><br><br>
      items:
        - name: Name
          icon: user
          icon_pack: fas
          description: <span style="font-size:90%">I Gaeun</span><br><br>
        - name: Date of Birth
          icon: calendar-days
          icon_pack: fas
          description:  <span style="font-size:90%">2003.01.23</span><br><br>
        - name: Location
          icon: location-dot
          icon_pack: fas
          description:  <span style="font-size:90%">Engineering Building 7, Chonbuk National University</span><br><br>
        - name: Contact
          icon: phone
          icon_pack: fas
          description:  <span style="font-size:90%">+82-5906-5988</span><br><br>
        - name: Email
          icon: envelope
          icon_pack: fas
          description:  <span style="font-size:90%">igaeun8@gmail.com</span><br><br>
        - name: Education
          icon: pen
          icon_pack: fas
          description:  <span style="font-size:90%">Department of Computer Artificial Intelligence, Chonbuk National University</span><br><br>


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
        folders:
          - travel_jejudo
          - travel_fukuoka
          - travel_danang
    design:
      view: community/custom_card
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="/author/I Gaeun/" cta_text="Click me →" %}}
    design:
      columns: '1'
---
