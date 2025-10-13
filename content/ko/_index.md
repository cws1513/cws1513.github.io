---
# 홈페이지 제목은 비워두어 사이트의 기본 제목을 사용하도록 합니다.
title:
date: 2025-10-13
type: landing

sections:
  # 1. 이미지 슬라이더 섹션
  - block: slider
    content:
      slides:
        # 슬라이드 1: 즐거운 학교 생활
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

        # 슬라이드 2: 개발자가 되어가는 길
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

        # 슬라이드 3: 스트레스 해소를 위한 취미생활
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

  # 2. Hero 블록: 방문자를 처음 맞이하는 대표 섹션
  - block: hero
    content:
      title: |
        최우성의
        개발자 포트폴리오
      # content/authors/admin/ 폴더의 프로필 사진을 자동으로 가져옵니다.
      image:
        filename: avatar.png
      text: |
        <br>
        
        새로운 기술을 배우고 적용하는 것을 즐기는 프론트엔드 개발자 지망생입니다. 저의 성장 과정과 프로젝트들을 이곳에서 확인하실 수 있습니다.

  # 3. Collection 블록: 프로젝트 글 목록을 보여주는 섹션
  - block: collection
    id: posts
    content:
      title: 최근 프로젝트
      text: ''
      # 보여줄 글의 개수 (과제 요구사항에 맞게 3개 이상)
      count: 3
      # post 타입의 글만 보여줍니다.
      filters:
        page_type: post
      # 최신순으로 정렬
      order: desc
    design:
      # 'compact'는 깔끔한 목록 형태입니다.
      view: compact
      columns: '2'

  # 4. Contact 블록: 연락처 정보를 보여주는 섹션
  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
        프로젝트 협업 제안이나 기타 궁금한 점이 있으시면 편하게 연락 주세요.
      # 이메일, 전화번호, 소셜 링크 등은 authors/admin/_index.md 에서 자동으로 가져옵니다.
      autol-ink: true
    design:
      columns: '2'
---