---
title:
date: 2025-10-13
type: landing

sections:
- block: slider
  content:
    slides:
    - title: Joyful School Life
      content: 'A record of my growth at the Department of IT Information Engineering, Jeonbuk National University.'
      align: center
      background:
        image:
          filename: school.jpg
          filters: { brightness: 0.7 }
        position: center
        color: '#FFFFFF'
    - title: The Path to Becoming a Developer
      content: 'Learning and applying new technologies as I move toward my dream.'
      align: center
      background:
        image:
          filename: coding.jpg
          filters: { brightness: 0.7 }
        position: center
        color: '#FFFFFF'
    - title: Hobbies for Stress Relief
      content: 'Balancing life with various activities beyond coding.'
      align: center
      background:
        image:
          filename: hobby.jpg
          filters: { brightness: 0.7 }
        position: center
        color: '#FFFFFF'
  design:
    is_fullscreen: true
    loop: true
    interval: 3000

- block: about.biography
  id: about
  content:
    title: About Me
    username: admin

- block: resume_button_en

- block: contact_custom_en
  id: contact
  content:
    title: 📍 위치 및 연락처
  design:
    background:
      color: "#f9f9f9"
  body: |-
    <div class="container-fluid section-heading-wrapper text-center">
      <h1 class="section-heading">연락처</h1>
      <p class="section-subtitle">
        프로젝트 협업 제안이나 기타 궁금한 점이 있으시면 편하게 연락 주세요.
      </p>
    </div>
    <div class="container">
      <div style="margin-top: 1rem;">
        <i class="fas fa-envelope pr-2" aria-hidden="true"></i>
        <a href="mailto:cws1513@jbnu.ac.kr">cws1513@jbnu.ac.kr</a>
      </div>
      <div style="margin-top: 0.5rem;">
        <i class="fas fa-phone pr-2" aria-hidden="true"></i>
        <a href="tel:010-5191-3088">010-5191-3088</a>
      </div>
      <div style="margin-top: 0.5rem; margin-bottom: 2rem;">
        <i class="fas fa-map-marker-alt pr-2" aria-hidden="true"></i> 전주시
      </div>
      <iframe src="http://googleusercontent.com/maps/google.com/15" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>

- block: collection
  id: hobbies
  content:
    title: 'My Hobbies'
    count: 3
    filters:
      folders:
        - hobby  
  design:
    view: custom_view_a 
    columns: '3' 

- block: collection
  id: studies
  content:
    title: 'My Studies'
    count: 3
    filters:
      folders:
        - study  
  design:
    view: custom_view_b

- block: collection
  id: websites
  content:
    title: 'Favorite Websites'
    count: 3
    filters:
      folders:
        - websites 
  design:
    view: card
---
