---
# Leave the homepage title empty to use the site's default title.
title:
date: 2025-10-13
type: landing

sections:
 
  - block: hero
    content:
      title: |
        Woosung Choi's
        Developer Portfolio
      
      image:
        filename: avatar.png
      text: |
        <br>
        
        A frontend developer aspirant who enjoys learning and applying new technologies. You can check out my growth process and projects here.

 
  - block: collection
    id: posts
    content:
      title: Recent Projects
      text: ''
      
      count: 3
      
      filters:
        page_type: post
     
      order: desc
    design:
      
      view: compact
      columns: '2'

  
  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
        Please feel free to contact me for project collaboration proposals or any other questions.
     
      autolink: true
    design:
      columns: '2'
---