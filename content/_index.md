---
type: widget_page

# 메인 화면 섹션들
sections:
  - block: about.biography
    id: about
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
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
  - block: contact
    id: contact
    content:
      title: Contact
      text: Feel free to reach out for collaborations.
---
