---
type: widget_page

# 메인 화면 섹션들
sections:
  - block: about.biography
    content:
      username: admin
  - block: collection
    id: publications
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
    design:
      view: citation # 연구자는 citation 뷰가 가장 깔끔합니다.
  - block: collection
    id: projects
    content:
      title: Research Projects
      filters:
        folders:
          - project
    design:
      view: card
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      text: Feel free to reach out for collaborations.
---
