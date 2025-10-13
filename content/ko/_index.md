---
title:
date: 2025-10-13
type: landing

sections:
  # 1️⃣ 슬라이더
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

  # 2️⃣ 자기소개 섹션
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

  # 3️⃣ 💬 연락처 섹션 (기능 이동 완료)
  - block: contact
    id: contact
    content:
      title: 연락처
      text: |-
        📞 프로젝트나 협업 문의가 있으신가요?  
        아래 버튼을 눌러 이메일·전화번호를 확인하거나,  
        소셜 링크를 클릭해 주세요.
      actions:
        - label: 이메일 및 전화번호 보기
          url: '/ko/contact/'        # ✅ contact.md 페이지로 이동
          icon_pack: fas
          icon: envelope
        - label: GitHub 방문하기
          url: 'https://github.com/cws1513'
          icon_pack: fab
          icon: github
        - label: Instagram
          url: 'https://instagram.com/choiwoosseong'
          icon_pack: fab
          icon: instagram
      autolink: false
    design:
      columns: '1'
      background:
        color: '#f9f9f9'

  # 4️⃣ 💼 프로젝트 섹션 (연락처 기능 제거 완료)
  - block: collection
    id: projects
    content:
      title: 프로젝트
      text: ''
      count: 3
      filters:
        section: post
        page_type: post
      #order: desc
    design:
      view: compact
      columns: '2'
---
