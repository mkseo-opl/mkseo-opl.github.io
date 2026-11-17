---
title:
type: landing

sections:
  - block: resume-biography-3
    content:
      username: admin
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: news
    content:
      title: Latest News
      subtitle: ''
      text: ''
      count: 5
      filters:
        folders:
          - post
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
---
