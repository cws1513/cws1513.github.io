---
title: 'Home'
date: 2023-10-24
type: landing

# Page sections
sections:
  # ⬇️ 이 블록이 Hero 위젯의 역할을 합니다.
  - block: biography
    id: about
    content:
      # content/authors/admin/ 폴더의 정보를 사용하라고 지정합니다.
      username: admin
      # 버튼 설정
      button:
        text: 이력서 다운로드
        url: uploads/resume.pdf # ⬅️ static/uploads/ 폴더에 이력서 파일이 있어야 합니다.
    design:
      # 상단에 표시될 배경 이미지 설정
      banner:
        filename: 'assets/media/kalen-emsley-Bkci_8qcdvQ-unsplash.jpg' # ⬅️ assets/media/ 폴더에 있는 풍경 이미지 파일명
      # 프로필 사진(아바타) 설정
      avatar:
        shape: circle # ⬅️ 프로필 사진 모양을 원형으로
  # ⬆️ 이 블록 수정이 핵심입니다.

  - block: experience
    content:
      username: admin
      title: Experience
    design:
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
---