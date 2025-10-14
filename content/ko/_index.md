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
            filters:
              brightness: 0.7
          position: center
          color: '#FFFFFF'
      - title: 개발자가 되어가는 길
        content: '새로운 기술을 배우고 적용하며 꿈을 향해 나아갑니다.'
        align: center
        background:
          image:
            filename: coding.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#FFFFFF'
      - title: 스트레스 해소를 위한 취미생활
        content: '코딩 외의 다양한 활동으로 삶의 균형을 맞춥니다.'
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
    title: 자기소개
    username: admin

# --- 이 섹션의 개인정보를 모두 사용자님의 것으로 수정했습니다 ---
- block: contact
  id: contact
  content:
    title: 연락처
    text: |-
      프로젝트 협업 제안이나 기타 궁금한 점이 있으시면 편하게 연락 주세요.
    email: cws1513@jbnu.ac.kr
    phone: 010-5191-3088
    address:
      street: 전북대학교 공과대학 7호관
      city: 전주시
      region: 전라북도
      postcode: '54896'
      country: 대한민국
      country_code: KR
    autolink: true
  design:
    columns: '1'

- block: map
  content:
    provider: google
    # 공과대학 7호관의 정확한 좌표로 수정했습니다.
    latitude: '35.8485'
    longitude: '127.1272'
    zoom: 17

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