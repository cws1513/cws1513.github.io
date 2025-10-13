---
# 홈페이지 제목은 비워두어 사이트의 기본 제목을 사용하도록 합니다.
title:
date: 2025-10-13
type: landing

sections:
  # 1. 이미지 슬라이더 섹션 (변경 없음)
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

  # 2. 자기소개 섹션 (연락처로 이동하는 버튼 추가)
  - block: about.biography
    id: about
    content:
      title: 자기소개
      username: admin
      actions:
        - label: 연락하기
          url: '/contact/'
          icon_pack: fas
          icon: arrow-down
      


  # 3. 프로젝트 목록 섹션
  - block: collection
    id: projects
    content:
      title: 프로젝트
      text: ''
      count: 4
      filters:
        page_type: post
      order: desc
    design:
      view: compact
      columns: '2'
---