---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: v1/about
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  - block: markdown
    id: news
    content:
      title: News
      subtitle: ''
      text: |-
        {{< news "/content/newslist.dat" 5 >}}
    design:
      columns: '2'

  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      columns: '2'
      view: card

  - block: contact
    id: contact
    content:
      title: Contact
      email: ivan [dot] stresec [at] gmail [dot] com
      autolink: False
    design:
      columns: '2'
---
