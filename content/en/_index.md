---# Leave the homepage title blank to use the site's default title.
title:
date: 2025-10-13
type: landing

sections:
  # 1. Image Slider Section (No changes)
  - block: slider
    content:
      slides:
        - title: Enjoyable School Life
          content: 'A record of my growth in the Department of IT Information Engineering at Jeonbuk National University.'
          align: center
          background:
            image:
              filename: school.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#FFFFFF'
        - title: The Path to Becoming a Developer
          content: 'Moving towards my dream by learning and applying new technologies.'
          align: center
          background:
            image:
              filename: coding.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#FFFFFF'
        - title: Hobbies for Stress Relief
          content: 'Balancing life with various activities outside of coding.'
          align: center
          background:
            image:
              filename: hobby.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#FFFFFF'
    design:
      is_fullscreen: true
      loop: true
      interval: 5000

  # 2. About Me Section (A simple introduction without social links)
  - block: about.biography
    id: about
    content:
      title: About Me
      username: admin

  # 3. Contact Section (Displays social link icons)
  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
        Please contact me by clicking the social links.
      
      autolink: true
      
      
      social:
        - icon: instagram
          icon_pack: fab
          link: 'https://www.instagram.com/choiwoosseong/'
        - icon: github
          icon_pack: fab
          link: 'https://github.com/cws1513'
        - icon: youtube
          icon_pack: fab
          link: 'https://www.youtube.com/@Allright24_' 
        - icon: cv
          icon_pack: ai
          link: uploads/cv.pdf
    design:
      columns: '2'

  # 4. Project List Section
  - block: collection
    id: projects
    content:
      title: Projects
      text: ''
      count: 4
      filters:
        page_type: post
      order: desc
    design:
      view: compact
      columns: '2'
---