---
title:
date: 2025-10-14
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
    interval: 3000

- block: about.biography
  id: about
  content:
    title: 자기소개
    username: admin

- block: resume_button_ko

- block: contact_custom_ko
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
      <iframe src="google.com/maps/embed?pb=!1m18!1m12!1m3!1d103332.9511085018!2d127.0549449439811!3d35.82422345638018!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357023435b32616b%3A0x1b4c02f47c21c78!2z7KCE656R67aB64-EIOyjvOyjvA!5e0!3m2!1sko!2skr!4v1729065000000!5m2!1sko!2skr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>

# 33번 항목 (1/3 세트), 4번 항목 (1/3 뷰)
- block: collection
  id: set-1
  content:
    title: '프로젝트'
    text: '첫 번째 뷰(custom_view_a)로 3개의 항목을 표시합니다.'
    count: 3  # <--- 3개
    filters:
      folders:
        - post
  design:
    view: custom_view_a  # <--- 1단계에서 만든 뷰 이름 (다른 뷰 1)

# 33번 항목 (2/3 세트), 4번 항목 (2/3 뷰)
- block: collection
  id: set-2
  content:
    title: '프로젝트 세트 2 (커스텀 뷰 B)'
    text: '두 번째 뷰(custom_view_b)로 3개의 항목을 표시합니다.'
    count: 3  # <--- 3개
    filters:
      folders:
        - post
  design:
    view: custom_view_b  # <--- 1단계에서 만든 뷰 이름 (다른 뷰 2)

# 33번 항목 (3/3 세트), 4번 항목 (3/3 뷰)
- block: collection
  id: set-3
  content:
    title: '프로젝트 세트 3 (기본 뷰)'
    text: '세 번째 뷰(내장된 card 뷰)로 3개의 항목을 표시합니다.'
    count: 3  # <--- 3개
    filters:
      folders:
        - post
  design:
    view: card  # <--- 테마에 내장된 기본 뷰 (다른 뷰 3)
    columns: '2' 
---