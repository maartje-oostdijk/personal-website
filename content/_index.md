---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: World Maritime University
      company_url: ""
      date_start: "2023-01-01"
      description: |2-
          Responsibilities include:

          * Fisheries connectivity analysis

      location: Reykjavik (Iceland)
      title: Research Associate    
    - company: World Maritime University
      company_url: ""
      date_end: "2022-12-06"
      date_start: "2021-05-03"
      description: |2-
          Responsibilities include:

          * Social-ecological model
          * Interviews
          * Quantitative governance analysis

      location: Malmo (remote)
      title: Research Associate
    - company: University of Iceland & Stockholm University
      company_url: ""
      date_end: "2021-04-23"
      date_start: "2016-03-01"
      description: Studied fisheries management impact on target stocks, and modeling of climate change impacts on the marine ecosystem
      location: Reykjavik (Iceland) & Stockholm (Sweden)
      title: PhD student
    title: Experience
  design:
    columns: "3"
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Fishing opportunities
      tag: Fishing opportunities
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Publications
  design:
    columns: "2"
    view: citation
  id: Publications
#- block: collection
  #content:
   # filters:
     # folders:
     # - event
    #title: Recent & Upcoming Talks
  #design:
    #columns: "2"
   # view: compact
  #id: talks
- block: contact
  content:
    email: maartjeoostdijk@gmail.com
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
