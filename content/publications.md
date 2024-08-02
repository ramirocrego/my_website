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
    text: Click on each mark to display paper cover and pdf link <iframe width=100% height="630" name="iframe" allowfullscreen=true  src="https://ramirocrego.github.io/PapersMap//" style="solid black"></iframe>
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
    text: <table id="gsc_rsb_st"><thead><tr><th class="gsc_rsb_sth"></th><th class="gsc_rsb_sth">All</th><th class="gsc_rsb_sth">Since 2019</th></tr></thead><tbody><tr><td class="gsc_rsb_sc1"><a href="javascript:void(0)" class="gsc_rsb_f gs_ibl" title="This is the number of citations to all publications. The second column has the &quot;recent&quot; version of this metric which is the number of new citations in the last 5 years to all publications.">Citations</a></td><td class="gsc_rsb_std">662</td><td class="gsc_rsb_std">556</td></tr><tr><td class="gsc_rsb_sc1"><a href="javascript:void(0)" class="gsc_rsb_f gs_ibl" title="h-index is the largest number h such that h publications have at least h citations. The second column has the &quot;recent&quot; version of this metric which is the largest number h such that h publications have at least h new citations in the last 5 years.">h-index</a></td><td class="gsc_rsb_std">17</td><td class="gsc_rsb_std">15</td></tr><tr><td class="gsc_rsb_sc1"><a href="javascript:void(0)" class="gsc_rsb_f gs_ibl" title="i10-index is the number of publications with at least 10 citations. The second column has the &quot;recent&quot; version of this metric which is the number of publications that have received at least 10 new citations in the last 5 years.">i10-index</a></td><td class="gsc_rsb_std">23</td><td class="gsc_rsb_std">21</td></tr></tbody></table>
---