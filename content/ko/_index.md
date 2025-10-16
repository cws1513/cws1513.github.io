---
title:
date: 2025-10-13
type: landing

sections:
- block: slider
  content:
    slides:
    - title: 즐거운 학교 생활
      content: '전북대학교 IT정보공학과에서의 성장 기록'
      align: center
      background:
        image:
          filename: school.jpg
          filters: { brightness: 0.7 }
        position: center
        color: '#FFFFFF'
    - title: 개발자가 되어가는 길
      content: '새로운 기술을 배우고 적용하며 꿈을 향해 나아갑니다.'
      align: center
      background:
        image:
          filename: coding.jpg
          filters: { brightness: 0.7 }
        position: center
        color: '#FFFFFF'
    - title: 스트레스를 해소하는 취미생활
      content: '코딩 외의 다양한 활동을 통해 삶의 균형을 유지합니다.'
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
    title: 자기소개
    username: admin


- block: contact_custom
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
        <i class="fas fa-map-marker-alt pr-2" aria-hidden="true"></i> 전주
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3234.1213201548776!2d127.13446309999999!3d35.8460286!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x35702330dc920b9d%3A0x1d0d425396006646!2z7KCE67aB64yA7ZWZ6rWQIOqzteqzvOuMgO2VmSA37Zi46rSA!5e0!3m2!1sko!2skr!4v1760592759759!5m2!1sko!2skr" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>  </div>

- block: collection
  id: projects
  content:
    title: 프로젝트
    text: ''
    count: 3
    filters:
      folders:
        - post
  design:
    view: compact
    columns: '2'
---