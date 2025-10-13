---
# 홈페이지 제목은 비워두어 사이트의 기본 제목을 사용하도록 합니다.
title:
date: 2025-10-13
type: landing

sections:
 
  - block: hero
    content:
      title: |
        최우성의
        개발자 포트폴리오
      
      image:
        filename: avatar.png
      text: |
        <br>
        
        새로운 기술을 배우고 적용하는 것을 즐기는 프론트엔드 개발자 지망생입니다. 저의 성장 과정과 프로젝트들을 이곳에서 확인하실 수 있습니다.

  
  - block: collection
    id: posts
    content:
      title: 최근 프로젝트
      text: ''
      
      count: 3
      
      filters:
        page_type: post
     
      order: desc
    design:
     
      view: compact
      columns: '2'

 
  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
        프로젝트 협업 제안이나 기타 궁금한 점이 있으시면 편하게 연락 주세요.
      
      autolink: true
    design:
      columns: '2'
---