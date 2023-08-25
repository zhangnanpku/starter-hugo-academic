---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 'About'
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: posts
    content:
      title: News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      design:
      # Choose a layout view
      view: compact
      columns: '2'  
  #- block: collection
    #id: featured
    #content:
    #  title: Featured Publications
    #  filters:
    #    folders:
    #      - publication
    #    featured_only: true
    #design:
    #  columns: '2'
    #  view: card
  - block: collection
    content:
      title: Selected Publications
      #text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: zhangnan@fudan.edu.cn
      address:
        street: Zibin N210, 220 Handan Rd
        city: Shanghai
        postcode: '200433'
        country: China
    design:
      columns: '2'
---
