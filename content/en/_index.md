---
title: 
date: 2025-10-14
type: landing

sections:
- block: slider
  content:
    slides:
      - title: Enjoying Campus Life
        content: "A growth journey at the Department of IT Information Engineering, Jeonbuk National University."
        align: center
        background:
          image:
            filename: school.jpg
            filters: { brightness: 0.7 }
          position: center
          color: "#FFFFFF"
      - title: Becoming a Developer
        content: "Learning and applying new technologies while moving toward my dream."
        align: center
        background:
          image:
            filename: coding.jpg
            filters: { brightness: 0.7 }
          position: center
          color: "#FFFFFF"
      - title: Hobbies That Relieve Stress
        content: "Maintaining balance through various activities outside of coding."
        align: center
        background:
          image:
            filename: hobby.jpg
            filters: { brightness: 0.7 }
          position: center
          color: "#FFFFFF"
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
    title: "📍 Location & Contact"
  design:
    background:
      color: "#f9f9f9"
  body: |-
    <div class="container-fluid section-heading-wrapper text-center">
      <h1 class="section-heading">Contact</h1>
      <p class="section-subtitle">
        Feel free to reach out for collaboration proposals or any inquiries.
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
        <i class="fas fa-map-marker-alt pr-2" aria-hidden="true"></i> Jeonju, South Korea
      </div>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d103332.9511085018!2d127.0549449439811!3d35.82422345638018!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357023435b32616b%3A0x1b4c02f47c21c78!2z7KCE656R67aB64-EIOyjvOyjvA!5e0!3m2!1sen!2skr!4v1729065000000!5m2!1sen!2skr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>

- block: collection
  content:
    title: "My Hobbies"
    count: 3
    filters:
      folders: [hobby]
  design:
    view: custom_view_a
    columns: "3"

- block: collection
  content:
    title: "My Studies"
    count: 3
    filters:
      folders: [study]
  design:
    view: custom_view_b

- block: collection
  content:
    title: "Main Websites"
    count: 3
    filters:
      folders: [websites]
  design:
    view: custom_view_c
---
