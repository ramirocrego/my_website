---
date: "2024-05-19"
design:
  spacing: 2rem
sections:
- block: markdown
  id: section-1
  content:
    title: A map of my publications
    text: Click on each mark to display paper cover and pdf link <iframe width="850" height="500" name="iframe" allowfullscreen=true  src="https://ramirocrego.github.io/PapersMap//" style="solid black"></iframe>
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

- block: collection
  content:
    count: 10
    filters:
      folders:
      - papers
    text: 
    title: Peer-reviewed articles
  design:
    columns: 1
    fill_image: false
    view: compact
    
- block: collection
  content:
    filters:
      folders:
      - books
    text: 
    title: Books and book chapters
  design:
    columns: 1
    fill_image: false
    view: compact
    
- block: collection
  content:
    filters:
      folders:
      - posters
    text: Posters presented at conferences
    title: Posters
  design:
    columns: 1
    fill_image: false
    view: compact
    
title: Publications
type: landing
---
