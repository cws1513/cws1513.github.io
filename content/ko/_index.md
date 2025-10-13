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
    actions:
    - label: 연락처 보기
      url: '#contact'
      icon_pack: fas
      icon: arrow-down

- block: contact
  id: contact
  content:
    title: 연락처
    text: |-
      프로젝트 협업 제안이나 기타 궁금한 점이 있으시면 아래 연락처로 편하게 연락 주세요.
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
    title: 프로젝트
    text: ''
    count: 4
    filters:
      section: post
      tag: '프로젝트'
  design:
    view: compact
    columns: '2'
---