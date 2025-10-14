---
title:
date: 2025-10-13
type: landing

sections:
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

- block: about.biography
  id: about
  content:
    title: About Me
    username: admin

- block: contact
  id: contact
  content:
    title: Contact
    text: |-
      Please feel free to contact me for project collaboration proposals or any other questions using the contact information below.
    email: cws1513@jbnu.ac.kr
    phone: 010-5191-3088
    autolink: true
  design:
    columns: '1'
    background:
      color: '#f9f9f9'

- block: collection
  id: projects
  content:
    title: Projects
    text: ''
    count: 4
    filters:
      section: post
      page_type: post
  design:
    view: compact
    columns: '2'
---