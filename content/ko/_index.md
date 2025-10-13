---
# 홈페이지 제목은 비워두어 사이트의 기본 제목을 사용하도록 합니다.
title:
date: 2025-10-13
type: landing

sections:
  # 1. 이미지 슬라이더 섹션
  # 이 블록은 우리가 만든 이미지 슬라이더를 화면 맨 위에 표시합니다.
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

  # 2. 자기소개 (프로필) 섹션
  # 이 부분이 가장 중요합니다!
  # 'about.biography' 블록은 자기소개 페이지의 내용을 그대로 가져와 보여주는 마법 같은 기능입니다.
  - block: about.biography
    id: about
    content:
      title: About Me
      # username: admin 은 "content/authors/admin/" 폴더에 있는
      # _index.md 파일의 모든 정보(사진, bio, 소셜 링크)를 가져오라는 뜻입니다.
      username: admin

  # 3. Collection 블록: 프로젝트 글 목록을 보여주는 섹션
  # 이 블록은 post 폴더에 있는 프로젝트 글들을 자동으로 모아서 보여줍니다.
  - block: collection
    id: projects
    content:
      title: Projects
      text: ''
      count: 3
      filters:
        page_type: post
      order: desc
    design:
      view: compact
      columns: '2'
---