---
title: 'Home'
date: 2023-10-24
type: landing

# Page sections
sections:
  - block: biography
    id: about
    content:
      username: admin
      button:
        text: 이력서 다운로드
        url: uploads/resume.pdf
    design:
      # ⬇️ [수정] biography와 avatar에 아래 스타일을 적용합니다.
      biography:
        # 텍스트, 아이콘, 버튼 등 모든 글 요소를 가운데 정렬합니다.
        style: 'text-align: center;'
      avatar:
        shape: circle
        # 프로필 사진 자체를 가운데로 옮깁니다.
        style: 'margin: 0 auto;'
      # ⬆️ [수정]
      banner:
        filename: 'kalen-emsley-Bkci_8qcdvQ-unsplash.jpg'

  # ⬇️ [수정] 중복 표시되던 Experience 블록을 삭제하고 Education만 남깁니다.
  - block: experience
    content:
      username: admin
      title: Education
    design:
      is_education_first: true
  # ⬆️ [수정]

  - block: skills
    content:
      title: 'Skills & Hobbies'
      username: admin

  - block: awards
    content:
      title: Accomplishments
      username: admin
---