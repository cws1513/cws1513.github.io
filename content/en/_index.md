---
# Leave the homepage title empty to use the site's default title.
title:
date: 2025-10-13
type: landing

sections:
  # 1. Image Slider Section
  - block: slider
    content:
      slides:
        - title: Joyful School Life
          content: 'A record of my growth at Jeonbuk National University, Dept. of IT Information Engineering'
          align: center
          background:
            image:
              filename: school.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#FFFFFF'

        - title: On the Path to Becoming a Developer
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

  # 2. Hero Block
  - block: hero
    content:
      title: |
        Woosung Choi's
        Developer Portfolio
      # Automatically fetches the profile picture from content/authors/admin/
      image:
        filename: avatar.png
      text: |
        <br>
        
        A frontend developer aspirant who enjoys learning and applying new technologies. You can check out my growth process and projects here.

  # 3. Collection Block (Projects)
  - block: collection
    id: posts
    content:
      title: Recent Projects
      text: ''
      # Number of posts to show (3 or more for the assignment)
      count: 3
      # Show content of type "post"
      filters:
        page_type: post
      # Order by date descending
      order: desc
    design:
      # 'compact' view provides a clean list format.
      view: compact
      columns: '2'

  # 4. Contact Block
  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
        Please feel free to contact me for project collaboration proposals or any other questions.
      # Email, phone, and social links are automatically pulled from authors/admin/_index.md.
      autolink: true
    design:
      columns: '2'
---