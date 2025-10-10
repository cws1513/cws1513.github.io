---
title: 'Home'
date: 2023-10-24
type: landing

# Page sections
sections:
  - block: biography
    id: about # 메뉴에서 '#about'으로 연결하기 위한 ID
    content:
      username: admin
      # 자기소개 텍스트를 이곳에 직접 작성하거나,
      # admin 폴더의 _index.md 파일에 있는 summary를 자동으로 불러옵니다.
      text: ""
    design:
      # 배경으로 사용할 배너 이미지
      banner:
        filename: 'assets/media/kalen-emsley-Bkci_8qcdvQ-unsplash.jpg' # ⬅️ assets/media/ 폴더에 있는 풍경 이미지 파일명
      # 프로필 사진(아바타) 설정
      avatar:
        # admin 폴더의 프로필 사진을 사용합니다.
        # 이 블록이 있으면 username의 avatar 설정을 덮어씁니다.
        filename: '' # 비워두면 username의 avatar를 사용
        shape: circle # ⬅️ 프로필 사진 모양 (circle, square, rounded)
  # ⬆️ [수정] Biography 블록 설정 변경

  - block: experience
    content:
      username: admin
      title: Experience
    design:
      # Education 섹션을 먼저 표시할지 여부
      is_education_first: false

  - block: experience
    content:
      username: admin
      title: Education
    design:
      is_education_first: true

  - block: skills
    content:
      title: Skills
      username: admin

  - block: awards
    content:
      title: Accomplishments
      username: admin

  - block: contact
    id: contact
    content:
      title: Contact
      # 여기에 연락처 정보를 직접 추가할 수 있습니다.
---