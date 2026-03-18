---
date: "2024-05-19"
title: Publications
type: landing

design:
  spacing: 2rem
sections:
- block: markdown
  id: section-1
  content:
    title: A map of my publications
    text: "<div style='width:100vw; margin-left:calc(-50vw + 50%);'><iframe src='https://ramirocrego.github.io/PapersMap//' style='width:100%; height:70vh; border:1px solid black;' allowfullscreen></iframe></div>"
  design:
    columns: '1'
    css_class: "full-width"
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
    fill_image: true
    view: compact
    
- block: collection
  content:
    count: 5
    filters:
      folders:
      - books
    text: 
    title: Books and book chapters
  design:
    columns: 1
    fill_image: true
    view: compact
    
- block: collection
  content:
    count: 3
    filters:
      folders:
      - posters
    text: Posters presented at conferences
    title: Posters
  design:
    columns: 3
    fill_image: false
    view: compact

- block: markdown
  id: section-2
  content:
    title: "Google Scholar Metrics"
    text: <table id="gsc_rsb_st"><thead><tr><th class="gsc_rsb_sth"></th><th class="gsc_rsb_sth">All</th><th class="gsc_rsb_sth">Since 2019</th></tr></thead><tbody><tr><td class="gsc_rsb_sc1"><a href="javascript:void(0)" class="gsc_rsb_f gs_ibl">Citations</a></td><td class="gsc_rsb_std">996</td><td class="gsc_rsb_std">787</td></tr><tr><td class="gsc_rsb_sc1"><a href="javascript:void(0)" class="gsc_rsb_f gs_ibl">h-index</a></td><td class="gsc_rsb_std">22</td><td class="gsc_rsb_std">17</td></tr><tr><td class="gsc_rsb_sc1"><a href="javascript:void(0)" class="gsc_rsb_f gs_ibl">i10-index</a></td><td class="gsc_rsb_std">31</td><td class="gsc_rsb_std">27</td></tr></tbody></table>
---