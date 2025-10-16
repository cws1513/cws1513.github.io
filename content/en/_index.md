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
    interval: 5000

- block: about.biography
  id: about
  content:
    title: About Me
    username: admin

- block: contact_custom
  id: contact
  content:
    title: 📍 Location & Contact
  design:
    background:
      color: "#f9f9f9"
  body: |-
    <div class="container-fluid section-heading-wrapper text-center">
      <h1 class="section-heading">Contact</h1>
      <p class="section-subtitle">
        Feel free to contact me for project collaboration proposals or any questions.
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
        <i class="fas fa-map-marker-alt pr-2" aria-hidden="true"></i> Engineering Building 7, Jeonbuk National University
      </div>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3246.393161690461!2d127.1246255763569!3d35.84850097262175!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3570228a73b2287b%3A0x3b8b1a8f33e3871!2z7KCE67aA64yA7ZWZ6rWQIOqzteuNsOq1rCDqsIQgN-2ajOq0gA!5e0!3m2!1sko!2skr!4v1729054133744!5m2!1sko!2skr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>

- block: collection
  id: projects
  content:
    title: Projects
    text: ''
    count: 3
    filters:
      folders:
        - post
  design:
    view: compact
    columns: '2'
---
