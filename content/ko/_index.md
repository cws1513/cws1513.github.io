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
        image: {filename: school.jpg, filters: {brightness: 0.7}}
        position: center
        color: '#FFFFFF'
    - title: 개발자가 되어가는 길
      content: '새로운 기술을 배우고 적용하며 꿈을 향해 나아갑니다.'
      align: center
      background:
        image: {filename: coding.jpg, filters: {brightness: 0.7}}
        position: center
        color: '#FFFFFF'
    - title: 스트레스 해소를 위한 취미생활
      content: '코딩 외의 다양한 활동으로 삶의 균형을 맞춥니다.'
      align: center
      background:
        image: {filename: hobby.jpg, filters: {brightness: 0.7}}
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

# --- 연락처와 지도를 하나로 합친 최종 블록 ---
- block: markdown
  id: contact # 메뉴바와 연결하기 위한 ID
  content:
    title: 연락처
    subtitle: 프로젝트 협업 제안이나 기타 궁금한 점이 있으시면 편하게 연락 주세요.
    text: |-
      <div style="margin-top: 1rem;">
        <i class="fas fa-envelope pr-2" aria-hidden="true"></i><a href="mailto:cws1513@jbnu.ac.kr">cws1513@jbnu.ac.kr</a>
      </div>
      <div style="margin-top: 0.5rem;">
        <i class="fas fa-phone pr-2" aria-hidden="true"></i><a href="tel:010-5191-3088">010-5191-3088</a>
      </div>
      <div style="margin-top: 0.5rem; margin-bottom: 2rem;">
        <i class="fas fa-map-marker-alt pr-2" aria-hidden="true"></i>전북대학교 공과대학 7호관
      </div>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3248.16666799822!2d127.1246253152538!3d35.8485009801788!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357022e3a296e4c7%3A0x6c8c7c6a5a2a2e4!2z7JeN67KV64yA7ZWZ6rWQIOqzteuCqO2VmeyLiOq1rCDqs63rgqjtlZntmITsgrwxN-ydtA!5e0!3m2!1sko!2skr!4v1665640101123!5m2!1sko!2skr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  design:
    columns: '1'
    background:
      color: '#f9f9f9'

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