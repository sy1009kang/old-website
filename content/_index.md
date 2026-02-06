---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

# (optional) You can keep design spacing or remove it
design:
  spacing: "4rem"

sections:
  # Publications only
  - block: collection
    id: papers
    content:
      title: Publications
      subtitle: ""
      text: ""
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation
---
