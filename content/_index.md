---
type: widget_page

# 홈페이지 섹션 순서 설정
sections:
  - block: about.biography
    id: about
    content:
      username: admin # content/authors/admin/_index.md 파일을 불러옵니다.
    design:
      background:
        color: '#fff'

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation # 깔끔한 리스트 형태
      columns: '1'

  - block: experience
    id: experience
    content:
      title: Experience
      
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      view: card
      columns: '2'
---
