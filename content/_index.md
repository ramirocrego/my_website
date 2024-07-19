---
date: "2024-07-18"
design:
  spacing: 6rem
sections:
- block: hero
  design:
    background:
      color: black
      image:
        filename: /gazelle.jpg
        size: cover
        filters:
          brightness: 1
    css_class: dark
- block: resume-biography-3
  id: about
  content:
    button:
      text: Download CV
      url: uploads/resume.pdf
    text: ""
    username: admin
  design:
    background:
      color: black
      image:
        filename: /stacked-peaks.svg
        filters:
          brightness: 1
        parallax: false
        position: center
        size: cover
    css_class: dark
    spacing:
      margin:
      - 0
      - 0
      - 0
      - 0
      padding:
      - 1rem
      - 0
      - 0
      - 0

- block: markdown
  id: section-1
  content:
    title: A map of my publications
    subtitle: Click on each mark to display paper cover and pdf link
    text: <iframe width="850" height="500" name="iframe" allowfullscreen=true  src="https://ramirocrego.github.io/PapersMap//" style="solid black"></iframe>
  design:
    columns: '1'
    spacing:
          margin:
          - 0
          - 0
          - 0
          - 0
          padding:
          - 1rem

# - block: collection
#   content:
#     filters:
#       exclude_featured: false
#       folders:
#       - SelectedPapers
#     text: ""
#     title: Selected Publications
#   design:
#     view: compact

- block: resume-skills
  content:
    title: Skills and Hobbies
    username: admin
  design:
    columns: 2
    spacing:
        margin:
        - 0
        - 0
        - 0
        - 0
        padding:
        - 1rem
title: ""
type: landing
---
