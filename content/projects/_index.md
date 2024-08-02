---
cascade:
- _target:
    kind: page
    path: /projects/**
  params:
    show_breadcrumb: true
design:
  spacing: 3rem
sections:
- block: collection
  content:
    filters:
      folders:
      - projects
    title: Projects
    text: This is a list of projects I am working with students and collaborators. 

    author: "Ramiro D Crego"
    sort_by: 'Date'
  design:
    columns: 3
    fill_image: true
    view: article-grid
  id: projects
  
- block: markdown
  id: section-1
  content:
    title: Joining the team
    text: If you are a passionate and self-motivated student interested in conservation biology and/or ecology and looking for opportunities to conduct a Master's or Ph.D. at University College Cork, contact me with your ideas, interests, and CV. I do not currently have funding but I am willing to support fellowship applications. Make sure your interests and motivations comes along clear in your message and make sure your email stands out and does not look like a generic email created by AI.
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

summary: 
title: Projects
type: landing
---


